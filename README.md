# 5072 · Ikaskuntza Automatikoko Sistemak — BETA

Repositorio honen helburua **5072 · Ikaskuntza Automatikoko Sistemak** modulurako sortutako material didaktikoak eta demo interaktiboak modu egituratuan argitaratzea da.

## 🧪 UD4 · Erregresioa — Demo interaktiboak

### 1. Response Predictor · OLS
`demos/erregresio-lineala/`

- puntuak arrastatu;
- OLS zuzena berriro kalkulatu;
- hondarrak;
- `b₀`, `b₁`, MSE eta R²;
- `x` berri baterako iragarpena.

### 2. MAE · RMSE · R²
`demos/metrikak/`

- benetako eta iragarritako balioak;
- errore uniformea;
- outlier / errore handi bat;
- bias;
- baseline `ȳ`;
- hiru metrikek egoera berari nola erantzuten dioten.

### 3. Gradient Descent
`demos/gradient-descent/`

- regression line-a epoch bakoitzean;
- `w`, `b` eta MSE;
- learning rate;
- urrats bakarra edo exekuzio automatikoa;
- MSE haranaren mapa;
- `forward → loss → gradients → update`.

### 4. Ridge vs Lasso
`demos/ridge-lasso/`

- feature korrelazionatuak;
- `α` penalty interaktiboa;
- OLS / Ridge / Lasso koefizienteak;
- Ridge → shrinkage;
- Lasso → zero koefiziente posibleak.

## 📂 Beta egitura

```text
5072-ml-beta/
├── index.html
├── README.md
└── demos/
    ├── erregresio-lineala/
    │   └── index.html
    ├── metrikak/
    │   └── index.html
    ├── gradient-descent/
    │   └── index.html
    └── ridge-lasso/
        └── index.html
```

## 🌐 GitHub Pages

Repositorioaren erroan:

```text
Settings → Pages
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

Adibidez:

```text
https://ZURE-ERABILTZAILEA.github.io/5072-ml/
```

Demo zuzenak:

```text
/demos/erregresio-lineala/
/demos/metrikak/
/demos/gradient-descent/
/demos/ridge-lasso/
```

## 🧭 Ikaskuntza-ikuspegia

```text
ulertu
   ↓
ikusi
   ↓
kodeatu
   ↓
esperimentatu
   ↓
interpretatu
```

Helburua ez da algoritmoak mekanikoki erabiltzea, baizik eta **zer egiten duten, zergatik egiten duten eta noiz erabiltzea komeni den ulertzea**.

## 📌 Egoera

**BETA** — ikastaroa amaitzean notebook-ak, teoriak, irudiak, demo-ak eta ebaluazio-materialak egitura bateratu batean antolatuko dira.
