# base64ToPDF
Convertidor de base64 a PDF usando html y javascript


Base64 es un sistema de codificación que permite representar datos binarios mediante caracteres ASCII. Su nombre se debe a que utiliza 64 caracteres diferentes para codificar los datos: las letras mayúsculas y minúsculas del alfabeto inglés, los dígitos del 0 al 9 y los símbolos + y /. Además, se utiliza el signo = como relleno al final de la cadena codificada.

Las aplicaciones de Base64 son variadas, pero en general se utiliza cuando se necesita transmitir o almacenar datos binarios en medios que solo admiten caracteres ASCII. Algunos ejemplos son:

- El envío de correos electrónicos con archivos adjuntos. Los protocolos de correo electrónico como SMTP solo permiten enviar texto plano, por lo que los archivos binarios deben ser codificados en Base64 antes de ser enviados y luego decodificados por el receptor.
- La incrustación de imágenes o sonidos en páginas web. Al utilizar el formato data:URI, se puede incluir el contenido binario de una imagen o un sonido directamente en el código HTML de la página, sin necesidad de usar una URL externa. Esto reduce el número de peticiones al servidor y mejora el rendimiento de la página.
- La generación de tokens o claves de seguridad. Al codificar datos binarios en Base64, se obtiene una cadena de caracteres que es más fácil de manipular y almacenar que los bytes originales. Por ejemplo, se puede usar Base64 para generar una clave secreta para un algoritmo de cifrado o una firma digital.

