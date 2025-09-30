# 🧠 Task 07: Ethical Implications of Decision Making Using LLMs

## 🔍 Overview
This task explores how Large Language Models (LLMs) perform on reasoning and decision-support tasks using structured datasets. We examine the **limits and strengths** of LLMs when answering factual, statistical, and reasoning-based queries over a real-world dataset.

## 📂 Dataset Used
**team_stats_2003_2023.csv** — Contains NFL team statistics such as:
- Offensive and defensive yards
- Wins, losses, turnovers
- Passing and rushing yards
- Points scored and allowed

## 🎯 Goals
- Design **LLM prompts** to ask factual, statistical, and insightful questions.
- Compare LLM responses to **Python-based descriptive statistics** (Pandas, Polars, Pure Python).
- Evaluate the **accuracy**, **reasoning quality**, and **insightfulness** of LLM outputs.
- Reflect on ethical use and **decision-making risk tiers** when LLMs are used.

## 🧪 Notebooks
- `Pure_Python.ipynb` → Descriptive stats using native Python
- `Pandas_Stats.ipynb` → Stats and groupbys using Pandas
- `Polars_Stats.ipynb` → Fast group-wise stats with Polars
- `Prompt.ipynb` → LLM prompt design, evaluation, and reasoning

## 📊 Visualizations
Graphs include:
- Distribution of Wins and Losses
- Correlation of Total Yards vs. Wins
- Trends in Passing Yards (2003–2023)
- Team-wise playoff participation patterns

> See `visual insights.pdf` for detailed charts and visual commentary.

## 🧠 Prompt Types Used
- **Factual Prompts** (e.g., "Which team had the most wins in 2022?")
- **Statistical Prompts** (e.g., "What’s the average wins for teams with >4000 yards?")
- **Reasoning Prompts** (e.g., "Do teams with more turnovers lose more games?")
- **Insightful Prompts** (e.g., "What patterns emerge among playoff teams?")

## ✅ Final Evaluation
Prompts were evaluated based on:
- **Correctness**
- **Relevance**
- **Explanation Quality**

## 📌 Ethical Takeaways
- LLMs are useful for **exploratory thinking**, but may produce hallucinated or **plausible-sounding falsehoods**.
- They work best when paired with **data validation tools** like Pandas or Polars.
- Risk tiering is essential: Factual stats = ✅ Safe | Predictions = ⚠️ Caution | Decisions = ❌ Human Review Required

## 📘 Deliverables
- ✅ All Notebooks (.ipynb)
- ✅ Visual Report (visual insights.pdf)
- ✅ Prompt evaluations
- ✅ This README
- ✅ Submitted Qualtrics Form

---

Created by: **Unnati Modi**  
M.S. in Applied Data Science, Syracuse University  
