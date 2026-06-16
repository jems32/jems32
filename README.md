<div align="center">

```
     ██╗███████╗███╗   ███╗███████╗
     ██║██╔════╝████╗ ████║██╔════╝
     ██║█████╗  ██╔████╔██║███████╗
██   ██║██╔══╝  ██║╚██╔╝██║╚════██║
╚█████╔╝███████╗██║ ╚═╝ ██║███████║
 ╚════╝ ╚══════╝╚═╝     ╚═╝╚══════╝
```

**data science projects** — turning raw data into something that actually means something

[![Python](https://img.shields.io/badge/Python_3.11+-white?style=flat-square&logo=python&logoColor=3776AB&labelColor=white&color=3776AB)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-white?style=flat-square&logo=jupyter&logoColor=F37626&color=F37626)](https://jupyter.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-white?style=flat-square&logo=scikit-learn&logoColor=F7931E&color=F7931E)](https://scikit-learn.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-white?style=flat-square&logo=pytorch&logoColor=EE4C2C&color=EE4C2C)](https://pytorch.org)
[![License: MIT](https://img.shields.io/badge/MIT-white?style=flat-square&color=22c55e)](LICENSE)

</div>

---

## about

I build data science projects — from exploratory analysis to production-ready ML pipelines. This repo is my public lab: experiments, models, and the occasional beautiful mess.

> *"All models are wrong, but some are useful."* — George Box

---

## projects

| project | what it does | stack | status |
|---------|-------------|-------|--------|
| **neural-notes** | classifies handwritten notes with 94% accuracy | PyTorch · CNN | `done` |
| **stock-pulse** | LSTM time-series forecasting on S&P 500 | Keras · yfinance | `active` |
| **geo-cluster** | unsupervised clustering of geospatial mobility data | scikit-learn · folium | `done` |
| **churn-radar** | predicts customer churn 30 days ahead | XGBoost · SHAP | `testing` |
| **sentiment-wave** | real-time Twitter sentiment dashboard | HuggingFace · Streamlit | `active` |

---

## quick start

```bash
# clone
git clone https://github.com/jems32/data-science-projects.git
cd data-science-projects

# set up environment
python -m venv .venv
source .venv/bin/activate       # Windows: .venv\Scripts\activate

# install deps
pip install -r requirements.txt

# launch notebooks
jupyter lab
```

---

## stack

```
Data          →  pandas  ·  numpy  ·  polars
Visualization →  matplotlib  ·  seaborn  ·  plotly
ML            →  scikit-learn  ·  XGBoost  ·  LightGBM
Deep learning →  PyTorch  ·  Keras
NLP           →  HuggingFace Transformers  ·  spaCy
Deployment    →  Streamlit  ·  FastAPI  ·  Docker
```

---

## structure

```
jems/
├── neural-notes/
│   ├── data/
│   ├── notebooks/          ← exploratory work lives here
│   ├── src/
│   │   ├── model.py
│   │   ├── train.py
│   │   └── evaluate.py
│   └── README.md
├── stock-pulse/
├── geo-cluster/
├── churn-radar/
├── sentiment-wave/
├── requirements.txt
└── README.md
```

---

## methodology

Every project follows the same discipline:

```
1.  Explore       →  understand the data before touching it
2.  Clean         →  handle nulls, outliers, leakage
3.  Feature eng   →  domain knowledge > brute force
4.  Model         →  baseline first, complexity second
5.  Evaluate      →  right metric for the right problem
6.  Communicate   →  results that non-data people can act on
```

---

## stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jems32&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jems32&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## contributing

Found a bug? Have a dataset idea? PRs and issues are welcome.

```bash
git checkout -b feat/your-idea
git commit -m "feat: add your idea"
git push origin feat/your-idea
```

---

## reach me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-jems32-181717?style=for-the-badge&logo=github)](https://github.com/jems32)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@jems.dev)

</div>

---

<div align="center">
  <sub>built with care and too many jupyter kernels · © 2025 jems</sub>
</div>
