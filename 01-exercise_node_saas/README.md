1. Install Live Server
2. Saas
    - run: npx node-sass -w style.scss -o css
    > Con esto lo que estamos diciendo es que Node Sass deberá estar en modo vigilante sobre el fichero style.scss de modo que al guardar el fichero, lance un proceso de compilación. Y con el atributo -o css le estamos diciendo que la salida de ese fichero css generado, lo haga en una carpeta llamada css.
    - update html file
    > <link rel="stylesheet" href="css/style.css" type="text/css" />