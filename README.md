# Angular: comunicando-se com uma API via requisições HTTP

Repositório utilizado no curso: Angular: comunicando-se com uma API via requisições HTTP


### Remover versões anteriores do Angular:
```
npm uninstall -g @angular/cli
```

### Instalar a versão 16 do Angular:
```
 npm install -g @angular/cli@17.0.0
```

### Instalar o projeto
```
npm install
```

### Instalar o Backend
```
cd backend
npm i -g json-server@0.17.4
npm install
```

### Rodar o backend (na pasta do projeto backend)
```
npm run start:dev
```

### Inicializar o projeto (na pasta do projeto Angular)
```
ng serve --open
```

### Nota:
Se você estiver no Linux é possível que a instalação do Angular Cli quebre o terminal, fazendo com que ele não carregue corretamente. Caso isso aconteça:

1. Edite o arquivo oculto **~/.bashrc**.
2. Remova a última linha do comando Angular: "source <(ng completion script)".
3. Salve o arquivo.

