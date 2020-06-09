## Desfazendo as coisas

### Voltar a versão antes de fazer o commit
``` shell
git checkout
```

### Tirar o arquivo do staged
``` shell
git reset HEAD nome_arquivo
```

### Retornar o commit para staged
``` shell
git reset --soft hash_arquivo
```

### Retornar o commit para antes do staged
``` shell
git reset --mixed hash_arquivo
```

### Apagar o commit
``` shell
git reset --hard hash_arquivo
```