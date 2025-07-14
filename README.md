Librería Morse – Conversión y Audio

Descripción

La Librería Morse es un proyecto Java que permite:
- Convertir texto normal a código Morse y viceversa.
- Traducir texto a binario y decodificar binario a texto.
- Reproducir sonidos de puntos y rayas correspondientes al código Morse.

Fue desarrollada para integrarse como un .jar reutilizable en otros proyectos



CLASES Y FUNCIONES



--------------LibreriaMorse--------------
Contiene los métodos principales para todas las conversiones y validaciones:
- normalAMorse(String): Convierte texto en español a código Morse.
- morseANormal(String): Convierte código Morse a texto.
- palabraABinario(String): Traduce texto a su representación binaria (ASCII).
- binarioAAscii(String): Convierte binario a texto, validando la longitud y rango ASCII.
- normalAsonido(String): Convierte texto a Morse y reproduce su sonido.
- morseASonido(String): Reproduce el sonido de un código Morse ingresado.


Validaciones incluidas:
- Solo letras y espacios para texto normal.
- Solo . - / y espacios para Morse.
- Solo 0 y 1 para binario.
- Uso de JOptionPane para mostrar errores de entrada.



------------PruebaVisual (JFrame)-----------
Interfaz gráfica que permite probar la librería:
- Selector (JComboBox) para elegir la operación.
- Campos de texto (JTextField) para introducir datos.
- Botones para traducir o reproducir sonido.
- Muestra resultados en un JLabel.

Opciones disponibles:
- Normal a Morse
- Morse a Normal
- Morse a Audio
- Normal a Audio
- Normal a Binario
- Binario a Normal





COMO IMPORTAR EL .jar

1. Compila el proyecto en NetBeans (Botón derecho a Limpiar y construir).
2. Busca el archivo .jar en la carpeta /dist.
3. En el proyecto donde lo quieras usar:
   - Haz clic derecho en Bibliotecas → Agregar JAR/Carpeta.
   - Selecciona tu .jar.
4. Importa la clase en tu código:
   import morsafinal.LibreriaMorse;



Capturas de pantalla
---------------------


Autores
-------
- Oliver
- Noé
