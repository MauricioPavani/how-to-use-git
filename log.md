## Visualizando logs

### Exibir as alterações no arquivo

``` shell
git log
```
### Exibir também as informações sobre as branchs

``` shell
git log --decorate
```
### Filtrar as alterações por autor

``` shell
git log --author="Nome"
```

### Exibir quantos commits foram feitos, quem são os autores e quais são os nomes

``` shell
git shortlog
```

### Exibir quantos commits foram feitos e quem são os autores

``` shell
git shortlog -sn
```

### Exibe de forma gráfica a situação

``` shell
git shortlog --graph
```

### Verificar as alterações no arquivo
``` shell
git show hash
```
