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

```
ng : El t?rmino 'ng' no se reconoce como nombre de un cmdlet, funci?n, archivo de script o      
programa ejecutable. Compruebe si escribi? correctamente el nombre o, si incluy? una ruta de    
acceso, compruebe que dicha ruta es correcta e int?ntelo de nuevo.
En l?nea: 1 Car?cter: 1
+ ng serve -o
+ ~~
    + CategoryInfo          : ObjectNotFound: (ng:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

-- Solucion

Por tanto, el error es que en el sistema esta deshabilitada la ejecuci?n de scripts. Si abrimos el Windows PowerShell 
como administrador y ejecutamos el comando 
?Get-ExecutionPolicy?
nos tendr?a que devolver ?Unrestricted? o lo que es lo mismo 
?Restringido?
Para cambiar esta configuraci?n basta con ejecutar 
?Set-ExecutionPolicy Unrestricted?	
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
    "src/assets/css/bootstrap.min.css"
  ],
  "scripts": [
    "src/assets/js/popper.min.js",
    "src/assets/js/bootstrap.min.js"              
  ]
```  

Cuando instalamos boostrap con npm (angular.json)

```bash
npm install bootstrap
```

```bash
  "styles": [
    "src/styles.css",
    "./node_modules/bootstrap/dist/css/bootstrap.css"
  ],
  "scripts": [
    "./node_modules/bootstrap/dist/js/bootstrap.min.js"              
  ]
```  
