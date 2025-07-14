# Librería Morse

## 📖 Descripción
La **Librería Morse** es una herramienta desarrollada en Java que permite convertir texto normal a **código Morse**, **código binario** y viceversa. También incluye funciones para reproducir sonidos equivalentes al código Morse utilizando archivos de audio. Esta librería está diseñada para ser integrada fácilmente en otros proyectos mediante la exportación como un archivo `.jar`.  

Autores: **Oliver y Noé**  

---

## 🛠️ Código fuente

### **Clases principales**

- **LibreriaMorse.java**
  - Clase **final** que contiene métodos estáticos para las conversiones y reproducción de audio.
  - Maneja listas como `abecedario` y `morse` para relacionar letras con sus equivalentes Morse.
  - Incluye validaciones con `JOptionPane` para evitar entradas inválidas.
  - Métodos destacados:
    - `normalAMorse(String)`: Convierte texto normal a código Morse.
    - `morseANormal(String)`: Convierte código Morse a texto normal.
    - `palabraABinario(String)`: Transforma texto a código binario.
    - `binarioAAscii(String)`: Convierte código binario a texto ASCII.
    - `normalAsonido(String)` y `morseASonido(String)`: Reproducen sonidos correspondientes al texto en Morse.

- **PruebaVisual.java**
  - Interfaz gráfica desarrollada con **Java Swing** para probar las funcionalidades de la librería.
  - Incluye:
    - `JComboBox` para seleccionar la operación deseada.
    - `JTextField` para ingresar datos.
    - `JButton` para traducir y reproducir sonidos.
    - `JLabel` para mostrar los resultados.

---

## 📂 Estructura del proyecto

```
UsoLibreriaMorse
│
├── Source Packages
│   ├── usolibreriamorse
│   │   ├── PruebaVisual.java
│   │   ├── UsoLibreriaMorse.java
│   │
│   ├── usolibreriamorse.LibreriaValidacion
│       └── LibreriaMorse.java
│
├── Libraries
│   └── LibreriaMorse.jar
├── capturas
│   ├── Captura1.png
│   ├── Captura2.png
│   └── Captura3.png
```

---

## 📥 Instrucciones para importar el `.jar`

1. Exporta el proyecto de la librería como un archivo `.jar` desde NetBeans:  
   - Haz clic derecho sobre el proyecto → `Clean and Build`.  
   - El archivo `.jar` se generará en la carpeta `dist`.  

2. Abre el proyecto donde deseas usar la librería.  
3. Haz clic derecho sobre **Libraries** → `Add JAR/Folder`.  
4. Selecciona el archivo `LibreriaMorse.jar`.  
5. Importa la librería en tu código:  
   ```java
   import morsafinal.LibreriaMorse;
   ```

---

## 🖥️ Capturas de pantalla

### Interfaz de usuario
![Interfaz de usuario](capturas/Captura1.png)

### Selección de opciones
![Selección de opciones](capturas/Captura2.png)

### Resultado
![Resultado](capturas/Captura3.png)

---

## ✅ Características

- Conversión entre texto normal, Morse y binario.  
- Reproducción de sonidos equivalentes a código Morse.  
- Validaciones de entradas para evitar errores.  
- Fácil integración en otros proyectos mediante `.jar`.  

---


