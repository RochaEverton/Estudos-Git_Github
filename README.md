# Resumos Git - Github

Repositório para armazenar resumos de estudos referentes a Git e Github.

[Github - Everton Rocha](https://github.com/RochaEverton)

## 📖 Documentação Oficial:
- [Git/Docs](https://git-scm.com/doc)
- [Github/Docs](https://docs.github.com/pt)

## Guia de comandos mais usados: 

### 💻 [Comandos mais usados Repositório Local.](ComandosLocais.md)

### 💻 [Comandos mais usados Repositório Remoto.](ComandosRemoto.md)

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
