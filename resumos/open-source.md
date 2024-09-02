# Contribuindo em um projeto open-source 🐱‍👤

Realizar o fork do projeto escolhido para contribuição, e posteriormente efetuar a clonagem dele, no repositório local.

```
git clone "NomeRepositorioRemotoForkado"
```

É necessário conectar o repositório local, ao repositório original (repositório remoto - contribuição do projeto). 

Será realizado esse procedimento, para que nosso repositório local, esteja sempre atualizado.

```
git remote add upstream "NomeRepositorioRemotoOriginal"
```

Para visualizar as alterações realizadas, utilize o comando abaixo:
```
git remote -v
```

Para baixar e mesclar as alterações no seu repositório local, utilize o seguinte comando:
```
git pull upstream main
```

Atualizando o repositório remoto, através do repositório local:
```
git push origin main
```

Crie uma nova branch:
```
git checkout -b nomeBranch/diretorioContribuicao/seuNomeDeUsuario
```

Crie um arquivo markdown, via GitBash:
```
touch diretorioContribuicao/seuNomeDeUsuario.md
```

Para verificar se há alguma alteração para ser realizado o push, por meio do repositório local:
```
git status
```

Para enviar todas alterações para a Área de Staging:
```
git add .
```
ou Para enviar apenas as alterações dos diretórios indicados:
```
git add diretorioContribuicao/seuNomeDeUsuario.md
```

Acompanhamento das alterações:
```
git status
```

Realizar o commit:
```
git commit 
```

Acompanhamento dos status referente aos commits
```
git log
```

Envia as alterações para o seu repositório remoto:
```
git push origin nomeBranch/diretorioContribuicao/seuNomeDeUsuario.md
```