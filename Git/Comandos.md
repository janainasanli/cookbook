# Comandos

## Configuração

```sh
# lista configurações do git local
git config --list
```

```sh
# configura o usuário local
git config --global user.name "Janaina Sanli"
git config --global user.email janainasanli@gmail.com
```

```sh
# configura o github local
git config --global github.user janainasanli
git config --global github.token [SECRET]
```

## Terminal

```sh
# inicia um repositorio git vazio
git init

# adiciona o endereço remoto do repositorio git
git remote add origin https://github.com/janainasanli/cookbook.git

# visualiza o endereço do repositorio remoto
git remote -v

# visualiza os arquivos não comitados
git status

# adicionad todos os arquivos
git add . --all

# adiciona os arquivos a um commit
git commit -m 'Commit inicial'

# envia os arquvios para o remoto (primeira vez)
git push --set-upstream origin master

# envia os arquvios para o remoto
git push
```
