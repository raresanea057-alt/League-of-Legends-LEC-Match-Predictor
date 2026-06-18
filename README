<div align="center">

# 🎮 LEC Match Predictor

**Predicting professional League of Legends LEC matches using only pre-game information**

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logo=catboost&logoColor=black)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

</div>

---

## 📖 Overview

Most esports prediction projects accidentally use information that is only available **during or after** a match, such as:

- Gold difference
- Kill difference
- Objective control
- Vision score

While these features can improve accuracy, they make predictions unrealistic — that information simply isn't available before the game starts.

This project predicts **LEC match winners using only pre-game data**, making it a realistic simulation of how analysts and bettors would make predictions before champion select.

---

## 🏆 Results

| Model | Accuracy | Precision | Recall | F1 Score |
|:--|:--:|:--:|:--:|:--:|
| 🚀 **CatBoost** | **0.71** | **0.70** | **0.71** | **0.70** |
| 🌲 Random Forest | 0.67 | 0.66 | 0.67 | 0.66 |
| 📈 Logistic Regression | 0.62 | 0.61 | 0.62 | 0.61 |
| 🪙 Baseline *(always pick Fnatic)* | 0.53 | — | — | — |

> **Improvement over baseline**
> Baseline accuracy: `53%` → CatBoost accuracy: `71%` → **Relative improvement: +34%**

---

## 📊 Features

The model only uses information available **before** the match begins.

| Feature | Description |
|:--|:--|
| `team_winrate_last5` | Team win rate in the last 5 games |
| `opponent_winrate_last5` | Opponent's recent performance |
| `head_to_head_winrate` | Historical matchup record |
| `days_since_last_match` | Rest and preparation time |
| `playoff_indicator` | Whether the match is a playoff game |

<table>
<tr>
<td valign="top" width="50%">

### ✅ Allowed
- Team form
- Historical performance
- Schedule-related features
- Match context

</td>
<td valign="top" width="50%">

### ❌ Not Allowed
- Gold difference
- Kill difference
- Tower difference
- Dragon control
- Any in-game statistics

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![CatBoost](https://img.shields.io/badge/-CatBoost-FFCC00?style=flat-square&logo=catboost&logoColor=black)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 📂 Project Structure

```
LEC-Match-Predictor/
│
├── data/
│   └── lec_matches.csv
│
├── notebooks/
│   └── LEC_Match_Predictor.ipynb
│
├── models/
│   └── catboost_model.pkl
│
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/raresanea057-alt/League-of-Legends-LEC-Match-Predictor.git
cd League-of-Legends-LEC-Match-Predictor
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Launch the notebook**

```bash
jupyter notebook notebooks/LEC_Match_Predictor.ipynb
```

---

## 💡 Key Takeaway

Despite using only pre-game information, the model achieves **71% accuracy**, significantly outperforming a simple baseline strategy.

This demonstrates that historical performance, recent form, and matchup data contain substantial predictive power in professional League of Legends.

---

## 🔮 Future Improvements

- [ ] Champion draft prediction
- [ ] Player-level statistics
- [ ] Elo rating system
- [ ] Betting market comparison
- [ ] Live web dashboard
- [ ] Explainable AI with SHAP values

---

<div align="center">

Made with 🐉 by [AneaRares](https://github.com/raresanea057-alt)

</div>
