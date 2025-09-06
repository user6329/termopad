Termopad Analyzer con Python y Tkinter

Este proyecto es una aplicación de escritorio desarrollada en Python utilizando la librería Tkinter que permite analizar datos obtenidos de un termopad a partir de archivos Excel.

🔹 Funcionalidad

Cargar un archivo Excel con las columnas:

Tiempo (formato de hora o fecha-hora)

Temperatura (valores numéricos)

Identificar automáticamente:

T1 → El tiempo y temperatura en el rango 65.3°C a 65.7°C

T2 → El tiempo y temperatura en el rango 87.3°C a 87.9°C

T3 → El tiempo y temperatura de la temperatura máxima registrada

Calcular los intervalos de tiempo entre:

T1 → T2

T2 → T3

Mostrar los resultados en una interfaz gráfica sencilla y fácil de usar.

🛠️ Tecnologías utilizadas

Python 3

Tkinter (interfaz gráfica)

Pandas (procesamiento de datos)

OpenPyXL / xlrd (lectura de archivos Excel)

📂 Ejemplo de uso

Abrir la aplicación.

Presionar el botón "Cargar Excel".

Seleccionar un archivo con los datos del termopad.

Visualizar los resultados de T1, T2, T3 e intervalos directamente en la ventana.

🚀 Mejoras futuras

Exportar los resultados a un nuevo archivo Excel.

Añadir gráficos de temperatura vs tiempo.

Soporte para múltiples archivos en lote.
