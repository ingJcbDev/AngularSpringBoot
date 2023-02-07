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
ng : El término 'ng' no se reconoce como nombre de un cmdlet, función, archivo de script o      
programa ejecutable. Compruebe si escribió correctamente el nombre o, si incluyó una ruta de    
acceso, compruebe que dicha ruta es correcta e inténtelo de nuevo.
En línea: 1 Carácter: 1
+ ng serve -o
+ ~~
    + CategoryInfo          : ObjectNotFound: (ng:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

-- Solucion

Por tanto, el error es que en el sistema esta deshabilitada la ejecución de scripts. Si abrimos el Windows PowerShell 
como administrador y ejecutamos el comando 
«Get-ExecutionPolicy»
nos tendría que devolver «Unrestricted» o lo que es lo mismo 
«Restringido»
Para cambiar esta configuración basta con ejecutar 
«Set-ExecutionPolicy Unrestricted»	
```

###Si apartir de esto no funciona validar lo siguente

0. Validar Instalacion nodejs
1.  Valigar/agregar Path nodejs
2. Validar/Agregar Path de npm
3.  Validar Instalacién global de la Libreria (angular/cli)
4.  Validat/Agregar Fath de angular/eli
5. Ejecutar ng desde apm run

* [link](https://www.evernote.com/client/web?login=true#?n=fc524878-77d9-adeb-bb8e-9917cdf34726&)

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
### HERRAMIENTAS NECESARIAS PARA EL CURSO
* JDK (Java SE Development Kit) [link](https://www.oracle.com/co/java/technologies/downloads/)
* IDE Eclipse + Spring Tools (Eclipse IDE for Enterprise Java and Web Developers) [link](https://www.eclipse.org/downloads/packages/)
* Maven
* MYSQL
* Postman
