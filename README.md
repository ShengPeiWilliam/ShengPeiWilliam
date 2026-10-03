# Hi, I'm William

Master of Data Science student at UC Irvine, graduating December 2026 and seeking new grad Data Scientist and Analytics roles. U.S. citizen in Irvine, CA, no sponsorship needed, open to relocating.

I'm drawn to marketplace problems: pricing, incentives, and balancing supply and demand. I want to decide where a lever should go, and prove that it moved. To see a marketplace from the inside, I delivered for DoorDash and built [Rearview](https://rearview-driver.vercel.app/), a dashboard that turns a driver's delivery export into answers about their own work.

I work in R and Python, focused on **statistical modeling, A/B testing, and Bayesian inference**. I also build end-to-end pipelines on AWS, so my analysis isn't bottlenecked by data availability.

[![Portfolio](https://img.shields.io/badge/Portfolio-0F5C4D?style=for-the-badge&logo=vercel&logoColor=white)](https://william-chen.vercel.app/)
[![Rearview](https://img.shields.io/badge/Rearview-1A1A1A?style=for-the-badge)](https://rearview-driver.vercel.app/)
[![Resume](https://img.shields.io/badge/Resume-1A1A1A?style=for-the-badge)](https://william-chen.vercel.app/resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1A1A1A?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shengpeichen)

---
### Projects

**Marketplace Analytics**
- [Rearview](https://github.com/ShengPeiWilliam/rearview) ([live](https://rearview-driver.vercel.app/)): A dashboard for DoorDash dashers, built from their own delivery export. From two months of my own dashing: stacking saves the dasher 1.6 minutes per order, but a same-store stack costs the second customer eight.
- [Citi Bike Demand by Rider Type (BSTS)](https://github.com/ShengPeiWilliam/citibike-aws-pipeline): Bayesian structural time series on 1,065 days of trips. Members and casual riders respond to temperature alike, but working days split them by 1,000 rides.

**Statistical Modeling & Experimentation**
- [Marketing Campaign A/B Testing](https://github.com/ShengPeiWilliam/marketing-ab-testing): Bayesian and frequentist analysis on 588K users. The lift is statistically significant but practically negligible, until you segment by ad exposure.
- [Synthetic Data Fidelity in Rare Strata](https://github.com/ShengPeiWilliam/mimic-synthetic-fidelity): CART-based synthesis on 70,954 MIMIC-IV ICU stays. Positive-case count, not sample size, decides what is estimable, and synthesis attenuates the interaction regardless.
- [Bayesian Prior Sensitivity](https://github.com/ShengPeiWilliam/bayesian-prior-sensitivity): Bayesian logistic regression on `birthwt` (n=189) under three priors. Rare predictors, not small n, determine when the prior stops mattering.
- [Cookie Cats Retention Experiment](https://github.com/ShengPeiWilliam/bayesian-ab-testing): Mobile game experiment on 90K players. One-day retention is inconclusive, while seven-day retention clearly favors the earlier gate.
- [Bike Rental Count Regression (Poisson / NB GLM)](https://github.com/ShengPeiWilliam/bikerental-poisson): Count regression on daily bike rentals. Diagnoses severe overdispersion (variance/mean = 833) and resolves it with a Negative Binomial model.
- [Bike Rental Regression Baseline (OLS, Ridge, Lasso)](https://github.com/ShengPeiWilliam/bikerental-ml): Linear baseline for daily bike rentals, comparing OLS, Ridge, and Lasso under rolling-origin cross-validation with full residual diagnostics.

**Predictive Modeling**
- [Energy Demand Forecasting](https://github.com/ShengPeiWilliam/energy-consumption-forecasting): Power demand across three city zones. XGBoost cuts MAPE from above 20% to 1 to 3% at ten minutes ahead, rising with horizon.
- [Customer Churn Prediction](https://github.com/ShengPeiWilliam/telecom-churn-ml): Telecom churn classifier on 500K+ records. Traced a 32-point train/test accuracy gap to inconsistent splits and corrected it by restratifying.
- [StarCraft II Skill Classification](https://github.com/ShengPeiWilliam/skillcraft-ml): Reformulated a published pairwise task into 6-class multinomial classification, outperforming the baseline in 3 of 4 league pairs.

**Recommendation & Retrieval**
- [Two-Tower Retrieval](https://github.com/ShengPeiWilliam/movierec-two-towers): Two-tower neural retrieval for movie recommendation, trained on 100K implicit feedback interactions, indexed in ChromaDB and served via FastAPI.
- [UCI Dataset Assistant (RAG)](https://github.com/ShengPeiWilliam/askuci): RAG chatbot that answers questions about 689 UCI ML Repository datasets.

**Developer Tools**
- [PR Description Generator](https://github.com/ShengPeiWilliam/git-pr-generator): CLI that turns Git commits into structured PR descriptions, built on an agent skill framework.

---
### Experience

**Data Science Capstone Researcher**, University of California, Irvine (Sept. 2026 to Present)
- Characterizing how Ethereum DApps grow and decline over time using on-chain activity data, on a six-person graduate team.
- Building supervised models to test whether early on-chain activity predicts which DApps become popular.

**Project Engineer (Data Science Focus)**, SHINSOFT CO., LTD. (Aug. 2024 to Feb. 2025)
- Diagnosed model underperformance on 200K+ camera images using EfficientNet embeddings with PCA and t-SNE; found an indoor vs. outdoor distribution gap and fine-tuned a dedicated indoor model, lifting accuracy by 15%.
- Traced false positives to data scarcity in underrepresented scenes rather than model capacity; designed a GAN-based augmentation strategy for the minority-scene training set, improving precision by 5%.
