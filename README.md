# 5072 · Ikaskuntza Automatikoko Sistemak — BETA

Biltegi honen helburua **5072 · Ikaskuntza Automatikoko Sistemak** modulurako sortutako material didaktikoak eta demo interaktiboak modu egituratuan argitaratzea da.

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

- erregresio-zuzena epoch bakoitzean;
- `w`, `b` eta MSE;
- ikaskuntza-tasa (learning rate);
- urrats bakarra edo exekuzio automatikoa;
- MSE haranaren mapa;
- `forward → loss → gradients → update`.

### 4. Ridge vs Lasso
`demos/ridge-lasso/`

- ezaugarri korrelazionatuak;
- `α` zigor interaktiboa;
- OLS / Ridge / Lasso koefizienteak;
- Ridge → koefizienteen magnitudea kontrolatu;
- Lasso → koefiziente batzuk zerora.

### 5. Ridge vs Lasso · Futbolariaren balioa
`demos/ridge-lasso-futbola/`

- EA SPORTS FC estiloko feature-ak: OVR, AGE, PAC, SHO, PAS, DRI, DEF eta PHY;
- futbolari-profil desberdinak;
- OLS / Ridge / Lasso modeloen predikzioak eta koefizienteak;
- `α` aldatuz erregularizazioaren efektua;
- feature korrelazionatuen interpretazioa;
- modeloak eta ebaluazio-metrikak bereiztea.

> Oharra: futbol-demoak dataset sintetiko didaktikoa erabiltzen du. Ez dira EA SPORTS FC-ren edo futbol-merkatu errealaren balio ofizialak.

## 🧠 UD5 · Sare neuronalak eta Deep Learning — Demo interaktiboak

### 1. Activation Lab
`demos/activation-lab/`

- `z = Wx+b → a=f(z)`;
- Identity, Sigmoid, Tanh eta ReLU;
- aktibazioaren balioa eta deribatua;
- Linear Regression / Logistic Regression / neurona lotura;
- Softmax: logit-ak → probabilitateak → `argmax`.

### 2. XOR Playground
`demos/xor-playground/`

- XOR linealki banaezina;
- aktibazioa ON/OFF;
- geruza ezkutuaren errepresentazio-aldaketa;
- `geruza + aktibazio ez-lineala` zergatik den funtsezkoa;
- azken muga lineal batek errepresentazio berrian nola lan egin dezakeen.

### 3. Training Doctor
`demos/training-doctor/`

- underfitting / egokitze ona / overfitting;
- train eta validation loss kurbak;
- validation loss minimoa;
- Dropout;
- Early Stopping;
- Ridge/Lasso-rekin helburu komuna baina mekanismo desberdinak.

### 4. CNN Kernel Explorer
`demos/cnn-kernel-explorer/`

- pixel-sarrera editagarria;
- 3×3 kernel desberdinak;
- feature map;
- ReLU;
- MaxPool 2×2;
- weight sharing;
- Dense vs Conv2D lehen geruzako parametro kopurua.

## 📂 Beta egitura

```text
5072-ml/
├── index.html
├── README.md
└── demos/
    ├── erregresio-lineala/
    ├── metrikak/
    ├── gradient-descent/
    ├── ridge-lasso/
    ├── ridge-lasso-futbola/
    ├── activation-lab/
    ├── xor-playground/
    ├── training-doctor/
    └── cnn-kernel-explorer/
```

## 🌐 GitHub Pages

Biltegiaren erroan:

```text
Settings → Pages
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

Oinarrizko URLa:

```text
https://rbarrenago.github.io/5072-ml/
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

## 🕒 Noiz erabili demo bakoitza?

### UD4

```text
1. Response Predictor         → 1. ariketaren amaieran
2. MAE · RMSE · R²            → 2. ariketan
3. Gradient Descent           → 3. ariketaren hasieran eta bitartean
4. Ridge vs Lasso             → 4. ariketan
5. Ridge vs Lasso · Futbola   → 4. ariketaren amaieran / Scout AI aurretik
```

### UD5

```text
1. Activation Lab             → S1 aurretik / aktibazio-funtzioak azaltzean
2. XOR Playground             → S1 notebook-aren aurretik eta bitartean
3. Training Doctor            → S3 entrenamendua eta erregularizazioa
4. CNN Kernel Explorer        → S4 notebook-aren aurretik eta bitartean
```

UD5eko progresio kontzeptuala:

```text
z = Wx+b
   ↓
a = f(z)
   ↓
ez-linealtasuna / XOR
   ↓
backprop → gradienteak
   ↓
optimizer → pisuak eguneratu
   ↓
generalizazioa
   ↓
CNN · lokalitatea + weight sharing
```

## 📌 Egoera

**BETA** — ikastaroa amaitzean notebook-ak, teoriak, irudiak, demo-ak eta ebaluazio-materialak egitura bateratu batean antolatuko dira.
