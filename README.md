# Actividad Formativa 2: Simulación y análisis de señales con la transformada de Fourier

Repositorio creado para la simulación, análisis y visualización de señales en el dominio del tiempo y de la frecuencia utilizando Python.

## Descripción del proyecto
El objetivo de esta práctica es aplicar la Transformada Rápida de Fourier (FFT) para comprender cómo se representan las señales elementales tanto en su dominio temporal como en su espectro de frecuencia (magnitud y fase).

## Contenido del repositorio
- **`analisis_fourier.ipynb`**: Cuaderno de Google Colab que contiene la implementación completa del código en Python.
- **Gráficos de señales**: Visualizaciones generadas para el pulso rectangular, la función escalón y la señal senoidal.

## Herramientas y librerías utilizadas
- **Python 3**
- **NumPy**: Para la manipulación numérica y cálculo de la FFT (`np.fft.fft`).
- **Matplotlib**: Para la representación gráfica de las señales y sus espectros.
- **Google Colab**: Entorno de desarrollo en la nube.

## Estructura del código
1. **Definición de parámetros**: Configuración de la frecuencia de muestreo y el intervalo de tiempo.
2. **Generación de señales**: Creación de la señal senoidal (50 Hz), el pulso rectangular y la función escalón.
3. **Cálculo de la Transformada de Fourier**: Aplicación de la FFT y obtención de los espectros de magnitud y fase para la mitad positiva de las frecuencias.
4. **Visualización**: Generación de gráficos comparativos de tiempo, magnitud y fase para cada señal.

## Autor
- **Oscar Steven Sigala Sauceda**
- Universidad Ciudadana de Nuevo León
