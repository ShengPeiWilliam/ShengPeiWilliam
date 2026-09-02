# Hi, I'm William

Master of Data Science student at UC Irvine (graduating December 2026), actively seeking new grad Data Scientist and Analytics roles (available early 2027). U.S. citizen based in Irvine, CA, authorized to work without sponsorship and willing to relocate.

I focus on **statistical modeling, A/B testing, and Bayesian inference**, working primarily in R and Python. Recent work has expanded into cloud data engineering on AWS, building end-to-end pipelines so my analysis isn't bottlenecked by data availability.  What I care about most is turning analysis into decisions someone can act on.

[![Portfolio](https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=vercel&logoColor=white)](https://william-chen.vercel.app/)
[![Resume](https://img.shields.io/badge/Resume-000?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1GgPjJEpnKY-LdWw60K4LBZ7-ie7LjV8o/view?usp=sharing)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shengpeichen)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ShengPeiWilliam)

---
### 🛠️ Projects

**Statistical Modeling & Experimentation**
- [Synthetic Data Fidelity in Rare Strata](https://github.com/ShengPeiWilliam/mimic-synthetic-fidelity) — CART-based synthesis (synthpop) on MIMIC-IV (n=70,954 ICU stays), the same question against a different generator: count, not sample size, decides what's estimable. The generator attenuates the interaction regardless.
- [Bayesian Prior Sensitivity](https://github.com/ShengPeiWilliam/bayesian-prior-sensitivity) — Prior sensitivity in Bayesian logistic regression on `birthwt` (n=189), showing that rare predictors, not small n, determine when the prior stops mattering. Deployed as an interactive Streamlit app on AWS EC2 with a Plumber API backend.
- [Marketing A/B Testing](https://github.com/ShengPeiWilliam/marketing-ab-testing) — Bayesian and Frequentist analysis on 588K users, exposing the gap between statistical significance and practical effect.
- [Cookie Cats A/B Testing](https://github.com/ShengPeiWilliam/bayesian-ab-testing) — Mobile game retention experiment showing why 1-day and 7-day metrics tell different stories about gate placement.
- [Bike Sharing Demand Forecasting (BSTS)](https://github.com/ShengPeiWilliam/citibike-aws-pipeline) — Bayesian structural time series quantifying how member and casual riders respond differently to weather, built on a self-constructed AWS data pipeline.
- [Bike Sharing Demand Forecasting (Poisson / NB GLM)](https://github.com/ShengPeiWilliam/bikerental-poisson) — Count regression diagnosing severe overdispersion (variance/mean = 833) and resolving it with Negative Binomial.
- [Bike Sharing Demand Forecasting (OLS)](https://github.com/ShengPeiWilliam/bikerental-ml) — Linear baseline with OLS, Ridge, Lasso under rolling-origin CV and full residual diagnostics.

**Predictive Modeling**
- [Energy Consumption Forecasting (XGBoost)](https://github.com/ShengPeiWilliam/energy-consumption-forecasting) — Power consumption forecasting across three zones of Tetouan, Morocco. XGBoost reduces MAPE from 21-27% to under 1%. Forecasting horizon and sampling frequency analysis quantify the deployment tradeoffs.
- [Customer Churn Prediction](https://github.com/ShengPeiWilliam/telecom-churn-ml) — Telecom churn classifier on 500K+ records, including a train/test distributional inconsistency diagnosis.
- [StarCraft II Skill Classification](https://github.com/ShengPeiWilliam/skillcraft-ml) — Reformulated a published pairwise task into 6-class multinomial classification, outperforming the baseline in 3 of 4 league pairs.

**Recommendation & Retrieval**
- [Two-Tower Retrieval](https://github.com/ShengPeiWilliam/movierec-two-towers) — Two-tower neural retrieval on 100K implicit feedback interactions, indexed in ChromaDB.
- [UCI Dataset Assistant (RAG)](https://github.com/ShengPeiWilliam/askuci) — Publicly deployed RAG chatbot indexing 689 UCI ML Repository datasets.

**Developer Tools**
- [PR Description Generator](https://github.com/ShengPeiWilliam/git-pr-generator) — CLI that turns Git commits into structured PR descriptions, built on an agent skill framework.

---
### 💼 Experience

**Project Engineer (Data Science Focus)** — SHINSOFT CO., LTD. (Aug 2024 – Feb 2025)
- Diagnosed model underperformance on 200K+ camera-captured images by extracting EfficientNet embeddings and applying PCA and t-SNE; identified indoor vs. outdoor distributional gap and fine-tuned a dedicated model on the underperforming indoor segment, lifting accuracy by 15%.
- Quantified data scarcity in underrepresented scenes as the root cause of false positives; designed a GAN-based augmentation strategy to expand the minority-scene training set, improving precision by 5%.
