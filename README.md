1-ACCEDEMOS A LA CARPETA QUE QUEREMOS PUBLICAR
C:\Users\wmiltos>cd..

C:\Users>cd..

C:\>cd \xampp\htdocs\facturacion

2-VERIFICAMOS EL ESTADO
C:\xampp\htdocs\facturacion>git status
fatal: not a git repository (or any of the parent directories): .git

3-INICIALIZAMOS GIT EN LA CARPETA
C:\xampp\htdocs\facturacion>git init
Initialized empty Git repository in C:/xampp/htdocs/facturacion/.git/

4-ACTIVAMOS LA CARPETA REMOTA
C:\xampp\htdocs\facturacion>git add -A
warning: LF will be replaced by CRLF in sistema/fonts/GothamBold.css.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in sistema/fonts/GothamBold.svg.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in sistema/js/756237d2e2.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in sistema/js/icons.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in sistema/js/jquery.min.js.
The file will have its original line endings in your working directory

5-VERIFICAMOS NUEVAMENTE EL STATUS
C:\xampp\htdocs\facturacion>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   conexion.php
        new file:   css/style.css
        new file:   img/login.png
        new file:   img/login2.png
        new file:   index.php
        new file:   sistema/ajax.php
        new file:   sistema/buscar_cliente.php
        new file:   sistema/buscar_proveedor.php
        new file:   sistema/buscar_usuario.php
        new file:   sistema/css/style.css
        new file:   sistema/editar_cliente.php
        new file:   sistema/editar_proveedor.php
        new file:   sistema/editar_usuario.php
        new file:   sistema/eliminar_confirmar_cliente.php
        new file:   sistema/eliminar_confirmar_proveedor.php
        new file:   sistema/eliminar_confirmar_usuario.php
        new file:   sistema/fonts/GothamBold.css
        new file:   sistema/fonts/GothamBold.eot
        new file:   sistema/fonts/GothamBold.otf
        new file:   sistema/fonts/GothamBold.svg
        new file:   sistema/fonts/GothamBold.ttf
        new file:   sistema/fonts/GothamBold.woff
        new file:   sistema/fonts/GothamBook.css
        new file:   sistema/fonts/GothamBook.eot
        new file:   sistema/fonts/GothamBook.svg
        new file:   sistema/fonts/GothamBook.ttf
        new file:   sistema/fonts/GothamBook.woff
        new file:   sistema/img/arrow_bottom.png
        new file:   sistema/img/img_producto.png
        new file:   sistema/img/salir.png
        new file:   sistema/img/uploads/img_107960b4667837d029ceeff192086677.jpg
        new file:   sistema/img/uploads/img_989fb1bf81f1e18757f458671a3145b6.jpg
        new file:   sistema/img/uploads/img_9f9eaecf17ed74485f7e4a423677137d.jpg
        new file:   sistema/img/uploads/img_a1e8d6cac603e222a3d3c0a3d7a1f577.jpg
        new file:   sistema/img/uploads/img_a71e8ab0e50284833969570a19935d06.jpg
        new file:   sistema/img/uploads/img_producto.jpg
        new file:   sistema/img/user.png
        new file:   sistema/includes/footer.php
        new file:   sistema/includes/functions.php
        new file:   sistema/includes/header.php
        new file:   sistema/includes/nav.php
        new file:   sistema/includes/scripts.php
        new file:   sistema/index.php
        new file:   sistema/js/756237d2e2.js
        new file:   sistema/js/functions.js
        new file:   sistema/js/icons.js
        new file:   sistema/js/jquery.min.js
        new file:   sistema/lista_clientes.php
        new file:   sistema/lista_producto.php
        new file:   sistema/lista_proveedor.php
        new file:   sistema/lista_usuarios.php
        new file:   sistema/registro_cliente.php
        new file:   sistema/registro_producto.php
        new file:   sistema/registro_proveedor.php
        new file:   sistema/registro_usuario.php
        new file:   sistema/salir.php

6-CARGAMOS LA VERSION DEL PROYECTO
C:\xampp\htdocs\facturacion>git commit -m "version 1"
[master (root-commit) c861a9b] version 1
 56 files changed, 5984 insertions(+)
 create mode 100644 conexion.php
 create mode 100644 css/style.css
 create mode 100644 img/login.png
 create mode 100644 img/login2.png
 create mode 100644 index.php
 create mode 100644 sistema/ajax.php
 create mode 100644 sistema/buscar_cliente.php
 create mode 100644 sistema/buscar_proveedor.php
 create mode 100644 sistema/buscar_usuario.php
 create mode 100644 sistema/css/style.css
 create mode 100644 sistema/editar_cliente.php
 create mode 100644 sistema/editar_proveedor.php
 create mode 100644 sistema/editar_usuario.php
 create mode 100644 sistema/eliminar_confirmar_cliente.php
 create mode 100644 sistema/eliminar_confirmar_proveedor.php
 create mode 100644 sistema/eliminar_confirmar_usuario.php
 create mode 100644 sistema/fonts/GothamBold.css
 create mode 100644 sistema/fonts/GothamBold.eot
 create mode 100644 sistema/fonts/GothamBold.otf
 create mode 100644 sistema/fonts/GothamBold.svg
 create mode 100644 sistema/fonts/GothamBold.ttf
 create mode 100644 sistema/fonts/GothamBold.woff
 create mode 100644 sistema/fonts/GothamBook.css
 create mode 100644 sistema/fonts/GothamBook.eot
 create mode 100644 sistema/fonts/GothamBook.svg
 create mode 100644 sistema/fonts/GothamBook.ttf
 create mode 100644 sistema/fonts/GothamBook.woff
 create mode 100644 sistema/img/arrow_bottom.png
 create mode 100644 sistema/img/img_producto.png
 create mode 100644 sistema/img/salir.png
 create mode 100644 sistema/img/uploads/img_107960b4667837d029ceeff192086677.jpg
 create mode 100644 sistema/img/uploads/img_989fb1bf81f1e18757f458671a3145b6.jpg
 create mode 100644 sistema/img/uploads/img_9f9eaecf17ed74485f7e4a423677137d.jpg
 create mode 100644 sistema/img/uploads/img_a1e8d6cac603e222a3d3c0a3d7a1f577.jpg
 create mode 100644 sistema/img/uploads/img_a71e8ab0e50284833969570a19935d06.jpg
 create mode 100644 sistema/img/uploads/img_producto.jpg
 create mode 100644 sistema/img/user.png
 create mode 100644 sistema/includes/footer.php
 create mode 100644 sistema/includes/functions.php
 create mode 100644 sistema/includes/header.php
 create mode 100644 sistema/includes/nav.php
 create mode 100644 sistema/includes/scripts.php
 create mode 100644 sistema/index.php
 create mode 100644 sistema/js/756237d2e2.js
 create mode 100644 sistema/js/functions.js
 create mode 100644 sistema/js/icons.js
 create mode 100644 sistema/js/jquery.min.js
 create mode 100644 sistema/lista_clientes.php
 create mode 100644 sistema/lista_producto.php
 create mode 100644 sistema/lista_proveedor.php
 create mode 100644 sistema/lista_usuarios.php
 create mode 100644 sistema/registro_cliente.php
 create mode 100644 sistema/registro_producto.php
 create mode 100644 sistema/registro_proveedor.php
 create mode 100644 sistema/registro_usuario.php
 create mode 100644 sistema/salir.php

7-PUBLICAMOS LA CARPETA EN LA DIRECCION CREADA EN EL GIT
C:\xampp\htdocs\facturacion>git remote add origin https://github.com/wilmiltoss/FacturacionPHP.git

8-ACTUALIZAMOS LA CARPETA PUBLICADA
C:\xampp\htdocs\facturacion>git push origin master
Enumerating objects: 64, done.
Counting objects: 100% (64/64), done.
Delta compression using up to 4 threads
Compressing objects: 100% (62/62), done.
Writing objects: 100% (64/64), 1.38 MiB | 319.00 KiB/s, done.
Total 64 (delta 9), reused 0 (delta 0)
remote: Resolving deltas: 100% (9/9), done.
To https://github.com/wilmiltoss/FacturacionPHP.git
 * [new branch]      master -> master

C:\xampp\htdocs\facturacion>
