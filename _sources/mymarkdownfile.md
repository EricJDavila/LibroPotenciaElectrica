# Aquí está mi título de ejemplo

Este es algún texto de ejemplo.

(section-label)=
## Aquí está mi primera sección

Aquí hay una referencia a [reference to the intro](intro.md). Aquí hay otra referencia a [](section-label).


```{figure} logo.png
:name: mi_figura_logo

Este es el título del logo.
```

Como se observa en la {numref}`mi_figura_logo`

```{table} El título de mi tabla
:name: mi_tabla_referencia

| Encabezado 1 | Encabezado 2 |
|---|---|
| 3 | 4 |
```

Es muy claro como se observa en la {numref}`mi_tabla_referencia`.

```{math}
:label: mi_ecuacion_referencia
w_{t+1} = (1 + r_{t+1}) s(w_t) + y_{t+1}
```

Vea el resultado en Ecuación {eq}`mi_ecuacion_referencia`.