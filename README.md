# Proyecto: Códigos de Huffman
Este proyecto realiza la compresión de imágenes bmp por medio de los códigos de Huffman por medio del lenguaje java
Integrantes:
- Hernández Montero Juan Carlos
- Montiel Gómez Erik Alain
## Pasos para compilar el problema
 1. Tener un IDE de java (El que se utilizó para la realización de la practica es IntelliJ IDEA)
 2. Cargar el proyecto
 3. Agregar las librerías anexas en este repositorio al proyecto
 4. Contar con imágenes bmp en blanco y negro
 5. Ejecutar el programa
## Como usar el programa
 1. Al ejecutar el programa se mostrará un botón para buscar los archivo
 2. Después se debe buscar y seleccionar la imagen a comprimir
 3. Al seleccionar la imagen será cargada al programa y se mostraran los siguientes datos:
    * Una tabla donde se mostraran los caracteres con los que está hecha la matriz, su frecuencia en la imagen y su código generado del árbol de Huffman
    * Se mostrara el tamaño inicial de la imagen (bits)
    * El tamaño final que tendrá el archivo ya comprimido
    * El porcentaje de compresión del archivo
 4. Se mostrarán también 2 pantallas emergentes mostrando lo siguiente
    * Una pantalla mostrará una gráfica de barras con los caracteres y su frecuencia
    * La otra mostrará el árbol generado 
 5. En la ruta donde se localiza la carpeta del proyecto se generará un archivo llamado "Resultado.txt" el cuál es el archivo comprimido
 6. Para poder volver a realizar una compresión unicamente se deben cerrar las ventanas emergentes (La gráfica y el árbol) y volver a presionar el botón para buscar otra imagen bmp
