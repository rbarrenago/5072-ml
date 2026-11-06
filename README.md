# 5072 · Ikaskuntza Automatikoko Sistemak — BETA

Repositorio honen helburua **5072 · Ikaskuntza Automatikoko Sistemak** modulurako sortutako material didaktikoak, notebook-ak eta demo interaktiboak modu egituratuan argitaratzea da.

Oraingoz, hau **Beta bertsioa** da. Lehenengo fase honetan baliabide interaktiboak argitaratzen hasiko gara; ikastaroa amaitzean, material guztia egitura bateratu batean antolatuko da.

---

## 🎯 Helburua

Repositorio honen bidez ikasleek Machine Learning-eko kontzeptuak ez bakarrik teorikoki, baizik eta **modu bisual, praktiko eta interaktiboan** ulertzea nahi dugu.

Helburu nagusiak:

- algoritmoen intuizioa ulertzea;
- kodearen eta matematikaren arteko lotura ikustea;
- modeloen portaera grafikoki esploratzea;
- esperimentatuz ikastea;
- Machine Learning-eko workflow osoa ulertzea.

---

## 🧪 Une honetan eskuragarri dagoen demo-a

### UD4 · Response Predictor — Erregresio lineala

Kokapena:

```text
demos/erregresio-lineala/index.html
```

Demo interaktibo honek **Least Squares / OLS erregresio lineala** modu bisualean ulertzeko aukera ematen du.

Ikasleak honako hauek egin ditzake:

- datu-puntuak arrastatu;
- OLS zuzena automatikoki berriro kalkulatzen ikusi;
- `ŷ = b₀ + b₁x` ekuazioa zuzenean ikusi;
- `b₀` eta `b₁` parametroak interpretatu;
- hondarrak (`residuals`) ikusi;
- MSE eta R² nola aldatzen diren aztertu;
- `x` berri baterako iragarpena egin;
- zarata, outlier-ak eta malda negatiboak probatu;
- puntu berriak gehitu.

Demo-ak ez du kanpoko liburutegirik erabiltzen eta `index.html` fitxategi bakar gisa funtzionatzen du.

---

## 📂 Oraingo Beta egitura

```text
5072-ml-beta/
├── index.html
├── README.md
└── demos/
    └── erregresio-lineala/
        └── index.html
```

Beta bertsio honen helburua ez da oraindik ikastaro osoaren egitura behin betiko definitzea.

Lehen urratsa baliabide interaktibo interesgarrienak modu garbian argitaratzen hastea da.

---

## 🌐 GitHub Pages bidez argitaratzea

1. GitHub-en repositorio berri bat sortu, adibidez:

```text
5072-ml
```

2. Repositorioaren `main` branch-era karpeta honetako edukia igo:

```text
index.html
README.md
demos/
```

3. GitHub-en joan:

```text
Settings
→ Pages
```

4. **Build and deployment** atalean aukeratu:

```text
Source:
Deploy from a branch

Branch:
main

Folder:
/ (root)
```

5. Aldaketak gorde.

Ondoren webgune nagusia honelako helbide batean egongo da:

```text
https://ZURE-ERABILTZAILEA.github.io/5072-ml/
```

Eta Linear Regression demo-a:

```text
https://ZURE-ERABILTZAILEA.github.io/5072-ml/demos/erregresio-lineala/
```

---

## 🚧 Etorkizunerako proposatutako egitura

Ikastaroa amaitzean, repositorioa honelako egitura batean antolatzea aurreikusten da:

```text
5072-ml/
├── index.html
├── README.md
│
├── ud2-datuak/
│   ├── notebooks/
│   ├── irudiak/
│   └── baliabideak/
│
├── ud3-sailkapena/
│   ├── notebooks/
│   ├── demos/
│   └── irudiak/
│
├── ud4-erregresioa/
│   ├── notebooks/
│   ├── demos/
│   └── irudiak/
│
├── ud5-deep-learning/
│   ├── notebooks/
│   ├── demos/
│   └── irudiak/
│
├── ud6-unsupervised/
│
├── ud7-balidazioa/
│
└── ebaluazioa/
```

Egitura hau **orientagarria** da eta ikastaroaren garapenaren arabera egokituko da.

---

## 🧭 Ikaskuntza-ikuspegia

Materialek ideia nagusi hau jarraitzen dute:

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

Helburua ez da algoritmoak mekanikoki erabiltzea.

Helburua da ikasleek ulertzea:

> **zer egiten duen modeloak, zergatik egiten duen eta noiz den egokia erabiltzea.**

---

## 🔬 5072 ML Lab

Etorkizunean repositorio hau **Machine Learning laborategi interaktibo txiki** bihurtzea da helburua.

Besteak beste:

```text
SVM prediction
xG predictor
Linear Regression / OLS
Gradient Descent
Decision Trees
Random Forest
Clustering
Neural Networks
Validation
```

bezalako kontzeptuak modu interaktiboan aztertzeko baliabideak gehituko dira.

---

## 🏫 Testuingurua

Material hau **Lanbide Heziketako 5072 · Ikaskuntza Automatikoko Sistemak** modulurako garatzen ari da.

Helburua Machine Learning-eko kontzeptuak FPko ikasleentzat:

- ulergarriak,
- bisualak,
- praktikoak,
- eta teknikoki zuzenak

izatea da.

---

## 📌 Egoera

```text
BETA
```

Repositorioa oraindik garatzen ari da.

Ikastaroa amaitzean material guztiak berrikusi, egituratu eta dokumentazio bateratua sortuko da.
