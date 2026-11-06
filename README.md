# 5072 · Ikaskuntza Automatikoko Sistemak — BETA

Repositorio Beta para ir publicando los materiales interactivos del módulo **5072** antes de estructurar el curso completo.

## Demo disponible

### UD4 · Response Predictor — Erregresio lineala
`demos/erregresio-lineala/index.html`

Incluye:

- puntos arrastrables;
- cálculo OLS automático;
- recta `ŷ = b₀ + b₁x`;
- residuos;
- `b₀`, `b₁`, MSE y R²;
- predicción para un nuevo `x`;
- presets con ruido, outlier y pendiente negativa;
- posibilidad de añadir nuevos puntos.

No utiliza librerías externas. Funciona como un único `index.html`.

## Estructura Beta

```text
5072-ml-beta/
├── index.html
├── README.md
└── demos/
    └── erregresio-lineala/
        └── index.html
```

## Publicar con GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `5072-ml`.
2. Subir el contenido de esta carpeta a la rama `main`.
3. Abrir **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Seleccionar `main` y `/ (root)`.
6. Guardar.

La página principal quedará en:

`https://TU-USUARIO.github.io/5072-ml/`

Y el demo:

`https://TU-USUARIO.github.io/5072-ml/demos/erregresio-lineala/`

## Estructura futura propuesta

Cuando finalice el curso:

```text
5072-ml/
├── index.html
├── README.md
├── ud2-datuak/
├── ud3-sailkapena/
│   ├── notebooks/
│   ├── demos/
│   └── irudiak/
├── ud4-erregresioa/
│   ├── notebooks/
│   ├── demos/
│   └── irudiak/
├── ud5-deep-learning/
├── ud6-unsupervised/
├── ud7-balidazioa/
└── ebaluazioa/
```

La Beta no intenta cerrar todavía esa arquitectura. Solo crea una base limpia para empezar a publicar recursos interactivos.
