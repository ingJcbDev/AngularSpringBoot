# Angular y Spring Boot

Version node

```bash
node -v
```

Version npm

```bash
npm -v
```

Install typescript para tener la sintaxis

```bash
npm install -g typescript
```

Version ts

```bash
tsc -v
npm list typescript -g
```

Install Angular

```bash
npm install -g @angular/cli
```

Version Angular
```bash
ng version
```

Crear un nuevo proyecto en angular

```bash
ng new clientes-app
```

## server angular

encender y abriri en el navegador

```bash
ng serve -o
```

## Crear componente con comandos
Nos ubicamos en el directorio
CD \Spring5 \ angular \ clientes - app \ src \ app \ footer > 

```bash
ng generate class footer/footer.component
```

se cambia el nombre de la class Footer.component a este FooterComponent

## Generar un componente con comandos

```bash
ng generate component directiva
```

De forma abreviada 

```bash
ng g c directiva
```

## Generar un service 
```bash
ng generate service cliente
```

De forma abreviada 

```bash
ng g s cliente
```


## Para instalar boostrap

lo tenemos asi
```bash
  <!-- CSS only -->
  <link href="assets/css/bootstrap.min.css" rel="stylesheet">
  <!-- JavaScript Bundle with Popper -->
  <script src="assets/js/popper.min.js"></script>
  <script src="assets/js/bootstrap.min.js"></script>
```  

pero lo podemos dejar asi en el archivo (angular.json)

```bash
"styles": [
    "src/styles.css",
    "assets/css/bootstrap.min.css"
],
"scripts": [
    "assets/js/popper.min.js",
    "assets/js/bootstrap.min.js"
]
```  
