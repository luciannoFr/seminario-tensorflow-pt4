
## TensorFlow\.js modelo secuencial parte 2

Este proyecto es una demostración simple de un modelo de regresión lineal utilizando **TensorFlow\.js**. El modelo aprende la fórmula `y = 2x + 6` a partir de datos de entrenamiento, y permite ingresar valores de `x` para obtener predicciones de `y`. Además, muestra una gráfica con la evolución de la pérdida (loss) durante el entrenamiento.

### Instalación y uso

1. Cloná este repositorio:

```bash
git clone https://github.com/luciannoFr/seminario-tensorflow-pt4
```

2. Ingresá a la carpeta del proyecto:

```bash
cd seminario-tensorflow-pt4
```

3. Instalá las dependencias:

```bash
npm install
```

4. Iniciá el servidor:

```bash
node server.js
```

5. Abrí tu navegador y entrá a:
   **[http://localhost:3000](http://localhost:3000)**

### ¿Qué hace este proyecto?

* Entrena un modelo secuencial con una sola capa densa usando TensorFlow\.js.
* Permite hacer predicciones para nuevos valores de `x`.
* Muestra una gráfica de la pérdida acumulada en cada entrenamiento con Plotly.
* Usa TailwindCSS para una interfaz simple y moderna.
