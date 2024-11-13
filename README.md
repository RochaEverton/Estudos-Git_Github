# Resumos Git - Github

Repositório para armazenar resumos de estudos referentes a Git e Github.

[Github - Everton Rocha](https://github.com/RochaEverton)

### 📖 Documentação Oficial:
- [Git/Docs](https://git-scm.com/doc)
- [Github/Docs](https://docs.github.com/pt)

### 💻 Comandos mais usados:
| comando | descrição | opções|
|---------|-----------|-------|
|git init| Iniciar Repositório ||
|git clone <URL>|clonar Repositório|Alterar nome do Repositório|
|git status|verifica o status dos arquivos||
|git add <Arquivo>|Informar os arquivos que serão submetidos |"*"ou"." insere todos os arquivos modificados/criados|
|git commit -m"<message>|Adiciona uma messagem ao commit|--amend altera a messagem do ultimo commit.|
|git log|Histórico de commits||
|git reflog| Histórico de commits com referências||
|git restore <arquivo>|Desfaz as alterações||
|git reset --<opção> <hash>|Desfazer o ultimo commit|--soft --mixed --hard|
|git push|Envia as alterações para o repositório remoto||

### ⚠️ Lembretes importantes:
```
.gitignore 
```
- arquivo onde são inseridos os arquivos que não serão acessíveis.

```
.gitkeep 
```
- Git não reconhece diretórios vázios por convenção é inserido o .gitkeep dentro dos diretórios que desejamos que sejam visíveis mesmo se for um diretório vazio.

```
rm -rf .git 
```
- Remove recursivamente o versionamento da pasta junto com seu conteúdo.
