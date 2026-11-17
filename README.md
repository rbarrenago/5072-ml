# 5072 · Ikaskuntza Automatikoko Sistemak — BETA

Biltegi honen helburua **5072 · Ikaskuntza Automatikoko Sistemak** modulurako sortutako material didaktikoak eta demo interaktiboak modu egituratuan argitaratzea da.

Materialek ikaskuntza-ikuspegi bera jarraitzen dute:

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

---

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
- ikaskuntza-tasa (*learning rate*);
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
- Lasso-k koefiziente batzuk 0 bihurtzeko duen gaitasuna;
- modeloak eta ebaluazio-metrikak bereiztea.

> Oharra: futbol-demoak dataset sintetiko didaktikoa erabiltzen du. Ez dira EA SPORTS FC-ren edo futbol-merkatu errealaren balio ofizialak.

### UD4 · Ibilbide kontzeptuala

```text
Zein da eredua?
      ↓
Nola neurtzen dugu errorea?
      ↓
Nola ikasten du?
      ↓
Nola kontrolatzen dugu konplexutasuna?
      ↓
Nola aplikatzen eta interpretatzen dugu testuinguru batean?
```

---

## 🧠 UD5 · Sare Neuronalak eta Deep Learning — Demo interaktiboak

### 1. XOR Playground
`demos/xor-playground/`

- neurona bakar baten muga lineala;
- XOR arazoa;
- zergatik ez den linealki banagarria;
- hidden layer baten beharra;
- ez-linealtasunaren intuizioa.

### 2. Logistic Regression vs Neural Network
`demos/logistic-vs-neural/`

- Titanic-like dataset sintetiko didaktikoa;
- dataset-eko row bat input vector bihurtzea;
- feature bakoitza input layer-eko neurona gisa ikustea;
- Logistic Regression → neurona bakarra + sigmoidea;
- MLP → `input → hidden layer → output`;
- fully connected konexioak;
- hidden neuron-en aktibazioak;
- modelo sinple eta sare neuronal baten arteko konparazioa.

### 3. Activation Lab
`demos/activation-lab/`

- Sigmoid;
- Tanh;
- ReLU;
- aktibazio-funtzioen portaera;
- ez-linealtasunaren rola;
- sare neuronal bateko aktibazioen intuizio bisuala.

### 4. Feature Combination Lab
`demos/feature-combination-lab/`

- XOR, moons eta circles dataset sintetikoak;
- problema ez-linealak;
- hidden neuron bakoitzak feature-en konbinazio desberdinak ikastea;
- hidden representation;
- datuen espazioa geruzaz geruza eraldatzea;
- hierarchical representation;
- azken neurona batek espazio eraldatuan erabaki lineala hartzea.

### 5. MNIST MLP Lab
`demos/mnist-mlp-lab/`

- MNIST estiloko 28×28 digitua;
- `28×28 → 784` flatten transformazioa;
- `784 → 128 → 64 → 10` MLP arkitektura;
- Dense + ReLU geruzak;
- Softmax probabilitateak;
- `Shuffle pixels` bidez egitura espazialaren galera ikustea;
- MLP-tik CNN-rako zubi kontzeptuala.

> Oharra: demoak MNIST estiloko lagin sintetikoak eta Softmax simulazio didaktikoa erabiltzen ditu. Helburua mekanismoa bistaratzea da, ez TensorFlow modeloa browserrean entrenatzea.

### 6. Training Doctor
`demos/training-doctor/`

- train eta validation kurbak;
- underfitting;
- fit egokia;
- overfitting;
- entrenamenduaren diagnostikoa;
- generalizazioaren intuizioa.

### 7. CNN Kernel Explorer
`demos/cnn-kernel-explorer/`

- kernel / filter baten mugimendua;
- konboluzioaren kalkulua;
- feature map;
- irudiko patroi lokalak;
- CNN baten lehen geruzen intuizio bisuala.

### UD5 · Ibilbide kontzeptuala

```text
neurona bakarra
      ↓
XOR eta muga linealak
      ↓
MLP eta hidden layer
      ↓
aktibazio ez-linealak
      ↓
feature combination
      ↓
hidden representation
      ↓
MLP + irudiak
      ↓
flatten eta egitura espazialaren muga
      ↓
entrenamendua eta generalizazioa
      ↓
CNN eta arkitektura espezializatuak
```

---

## 📂 Beta egitura

```text
5072-ml/
├── .gitignore
├── index.html
├── README.md
└── demos/
    ├── erregresio-lineala/
    │   └── index.html
    ├── metrikak/
    │   └── index.html
    ├── gradient-descent/
    │   └── index.html
    ├── ridge-lasso/
    │   └── index.html
    ├── ridge-lasso-futbola/
    │   └── index.html
    ├── xor-playground/
    │   └── index.html
    ├── logistic-vs-neural/
    │   └── index.html
    ├── activation-lab/
    │   └── index.html
    ├── feature-combination-lab/
    │   └── index.html
    ├── mnist-mlp-lab/
    │   └── index.html
    ├── training-doctor/
    │   └── index.html
    └── cnn-kernel-explorer/
        └── index.html
```

---

## 🌐 GitHub Pages

Webgune nagusia:

```text
https://rbarrenago.github.io/5072-ml/
```

Demo zuzenak:

```text
https://rbarrenago.github.io/5072-ml/demos/erregresio-lineala/
https://rbarrenago.github.io/5072-ml/demos/metrikak/
https://rbarrenago.github.io/5072-ml/demos/gradient-descent/
https://rbarrenago.github.io/5072-ml/demos/ridge-lasso/
https://rbarrenago.github.io/5072-ml/demos/ridge-lasso-futbola/

https://rbarrenago.github.io/5072-ml/demos/xor-playground/
https://rbarrenago.github.io/5072-ml/demos/logistic-vs-neural/
https://rbarrenago.github.io/5072-ml/demos/activation-lab/
https://rbarrenago.github.io/5072-ml/demos/feature-combination-lab/
https://rbarrenago.github.io/5072-ml/demos/mnist-mlp-lab/
https://rbarrenago.github.io/5072-ml/demos/training-doctor/
https://rbarrenago.github.io/5072-ml/demos/cnn-kernel-explorer/
```

GitHub Pages konfigurazioa:

```text
Settings → Pages
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

---

## 🕒 Noiz erabili demo bakoitza?

### UD4

```text
1. Response Predictor         → erregresio lineala ulertzeko
2. MAE · RMSE · R²            → ebaluazio-metrikak lantzeko
3. Gradient Descent           → modeloak nola ikasten duen ulertzeko
4. Ridge vs Lasso             → erregularizazioa lantzeko
5. Ridge vs Lasso · Futbola   → aplikazioa eta interpretazioa
```

### UD5

```text
1. XOR Playground                         → neurona bakarraren muga
2. Logistic Regression vs Neural Network → LR-tik MLP-rako zubia
3. Activation Lab                         → ez-linealtasuna
4. Feature Combination Lab                → feature learning eta hidden representation
5. MNIST MLP Lab                          → MLP + irudiak; flatten eta CNN-rako zubia
6. Training Doctor                        → entrenamendua eta generalizazioa
7. CNN Kernel Explorer                    → CNN-en sarrera
```

---

## 📌 Egoera

**BETA**

Repositorioa oraindik garatzen ari da. Ikastaroak aurrera egin ahala notebook-ak, teoriak, irudiak, demo-ak eta ebaluazio-materialak egitura bateratu batean antolatuko dira.

Helburua da repositorio hau pixkanaka **5072 ML Lab** bihurtzea: Machine Learning eta Deep Learning kontzeptuak modu bisual, praktiko eta interaktiboan ikasteko laborategia.
