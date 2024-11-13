# Resumos Git - Github

Repositório para armazenar resumos de estudos referentes a Git e Github.

[Github - Everton Rocha](https://github.com/RochaEverton)

## 📖 Documentação Oficial:
- [Git/Docs](https://git-scm.com/doc)
- [Github/Docs](https://docs.github.com/pt)

## Guia de comandos mais usados: 

### 💻 Comandos Repositório Local.

|Lista de Comandos mais usados|Descrição|
|-------|---------|
|git init|inicia o repositório|
|git config|configurações do git|
|git status|verifica o estado dos arquivos|
|git add <arquivo>|adiciona os arquivos ao Staged|
|git commit -m"msg"|salva os arquivos localmente|


[Lista detalhada de comandos Repositório Local.](ComandosLocais.md)

### 💻 Comandos Repositório Remoto.

|Lista de Comandos mais usados|Descrição|
|-------|---------|
|git clone <URL>|clonar repositório remoto|
|git remote set-url <URL>|Altera a URL do repositório remoto|
|git push origin main|Envia as alterações para o repostório remoto|
|git pull origin main|Solicita as alterações do repositório remoto|

[Lista detalhada de comandos Repositório Remoto.](ComandosRemoto.md)

## ⚠️ Lembretes importantes:

- arquivo onde são inseridos os arquivos que não serão acessíveis.
```
.gitignore 
```

- Git não reconhece diretórios vázios por convenção é inserido o .gitkeep dentro dos diretórios que desejamos que sejam visíveis mesmo se for um diretório vazio.
```
.gitkeep 
```

- Remove recursivamente o versionamento da pasta junto com seu conteúdo.
```
rm -rf .git 
```

- testa a autenticação das chaves SSH.
```
ssh -T git@github.com
```
