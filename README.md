# Interfaz Grafica de Grafos y Matrices de Adyacencia
### Autores: Samuel Henao y Nicolás Ospina
### Language: Python (Version 3.12)  
### OS: Windows 11

## Descripción

Este programa fue creado como parte del curso **Estructura de Datos II**, enseñado por el docente Alexander de Jesus Narvaes en la **Universidad EAFIT.**
Esta aplicación, desarrollada en Python utilizando PyQt5, permite al usuario interactuar con grafos visuales y 
calcular sus matrices de trayectoria (adyacencia, cuadrada y cúbica). Los grafos son generados a partir de matrices de adyacencia introducidas por el usuario o de manera aleatoria.

La aplicación también incluye funcionalidades para:
- Generar matrices de adyacencia aleatorias.
- Calcular y mostrar la matriz cuadrada y cúbica de un grafo.
- Mostrar el grafo generado con nodos y aristas.

---

## Características Principales

1. **Interfaz gráfica:**
   - Vista de grafos interactiva con nodos y aristas.
   - Textos descriptivos de los pesos en las aristas.
   
2. **Manejo de matrices:**
   - Generación de matrices de adyacencia desde un `QTable`.
   - Cálculo de matrices cuadradas y cúbicas basadas en la matriz de adyacencia.

3. **Edición y generación:**
   - Personalización de la matriz de adyacencia desde la interfaz.
   - Generación aleatoria de grafos.

---

## Requisitos del Sistema

- Python 3.8 o superior.
- Librerías necesarias:
  - PyQt5
  - random (incluido en la biblioteca estándar de Python)

Instalar las dependencias necesarias con el siguiente comando:

```bash
pip install PyQt5
```
---

## Ejecución del Proyecto

1. **Clonar o descargar el repositorio.**

   ```bash
   git clone https://github.com/niosto/Interfaz-Grafica-de-Grafos-y-Matrices-de-Trayectoria.git
   cd Interfaz-Grafica-de-Grafos-y-Matrices-de-Trayectoria
   ```

2. **Ejecutar el archivo principal.**

   Desde la terminal, ejecutar:

   ```bash
   python main.py
   ```

3. **Interfaz gráfica:**
   - Se abrirá una ventana que mostrará la interfaz gráfica del programa.

---

## Funcionalidad

1. **Generar un Grafo:**
   - Llenar la matriz de adyacencia manualmente o generar valores aleatorios desde la barra de encabezado del `QTable`.
   - Pulsar el botón **"Pintar Grafo"** para visualizar el grafo generado en el área de visualización.

2. **Matrices de Trayectoria:**
   - Calcular la matriz cuadrada pulsando el botón **"Matriz Cuadrada"**.
   - Calcular la matriz cúbica pulsando el botón **"Matriz Cúbica"**.

3. **Visualizar Pesos y Conexiones:**
   - Los pesos de las aristas se mostrarán sobre las líneas que conectan los nodos en el grafo.

4. **Interactividad:**
   - Los nodos se pueden mover dentro de la vista para reorganizar el grafo.
   - Las aristas se ajustan automáticamente al reposicionar los nodos.

---

### Visualización de la Interfaz

- **Vista Principal de la Interfaz:**
  ![image](https://github.com/user-attachments/assets/e161c2e7-25b9-46e5-ba69-9a38cf70e244)

- **Grafo Generado:**
  ![image](https://github.com/user-attachments/assets/6d38cfd4-bd60-4970-9010-95c025682c35)

- **Matrices de Trayectoria:**
  ![image](https://github.com/user-attachments/assets/317c75ae-4658-4755-b991-a6aeabc65415)
