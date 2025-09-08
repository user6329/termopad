#  Termopad Analyzer

**Termopad** es una aplicación de escritorio desarrollada en **Python** con **Tkinter**, diseñada para analizar archivos de datos provenientes de un **termopar/termopad** en formato **Excel**.  

La aplicación permite cargar un archivo Excel con las columnas necesarias y extraer automáticamente puntos críticos de temperatura, junto con los intervalos de tiempo asociados.  

---

##  Características

- Carga de archivos Excel (`.xlsx`, `.xls`).
- Identificación automática de:
  - **Rt1:** Tiempo en que la temperatura alcanza 65.3 – 65.7 °C.  
  - **Rt2:** Tiempo en que la temperatura alcanza 87.3 – 87.9 °C.  
  - **T_exot:** Tiempo en que se alcanza la **temperatura más alta**.  
- Cálculo de intervalos de tiempo entre:
  - Rt1 → Rt2  
  - Rt2 → T_exot  
- Soporte para **dos termopares (Temperatura y Temperatura2)**.
- Interfaz gráfica amigable, con logotipo corporativo y estilos personalizados.
- Generación de ejecutable con **PyInstaller** para fácil distribución.

---

## Requisitos

- Python 3.9 o superior (desarrollado con Python 3.13.3).  
- Librerías necesarias:
  ```bash
  pip install pandas openpyxl pillow


Soporte para múltiples archivos en lote.
