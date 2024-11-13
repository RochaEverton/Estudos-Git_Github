# Resumos Git - Github

Repositório para armazenar resumos de estudos referentes a Git e Github.

[Github - Everton Rocha](https://github.com/RochaEverton)

### 📖 Documentação Oficial:
- [Git/Docs](https://git-scm.com/doc)
- [Github/Docs](https://docs.github.com/pt)

### 💻 Comandos mais usados Repositório Local:
```
git init 
```
- Iniciar uma repositório local.
```
git config 
```
- Verifica as configurações. (opções: --global / --local / --get)
```
git status 
```
- Verifica os arquivos "preparados" na área de Stage. 
```
git add <arquivo>
```
- Informa os arquivos que serão submetidos. (opções: "." ou "*" insere todos os arquivos modificados/criados).
```
git commit
```
- Salvar os arquivos no repositório local. (opção -m"message" insere uma mensagem com informações referentes ao commit).
```
git log
```
- Verifica o histórico de commits.
```
git reflog
```
- Verifica o histórico de commits com referências.
```
git restore <arquivo>
```
- Desfaz alterações.
```
git reset <hash>
```
- Alterações em commits. (opções: --soft / --mixed / --hard).
```

### 💻 Comandos mais usados Repositório Remoto:
```
git clone <URL>
```
- Clonar um repositório remoto.
```
git remote set-url <URL>
```
- Altera a URL do repositório remoto.
```
git push origin main
```
- Envia as alterações para o repostório remoto. (opções: <origin>refere-se ao repositório remoto <main> refere-se a branch)


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
```
ssh -T git@github.com
```
- testa a autenticação das chaves SSH.
