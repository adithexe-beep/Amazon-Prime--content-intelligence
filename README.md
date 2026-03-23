🎬 Amazon Prime Video: Content Intelligence & Rating Predictor

📌 Project Overview
This project leverages Natural Language Processing (NLP) and Advanced Ensemble Learning to predict IMDb ratings for content on Amazon Prime Video. It serves as a decision-support tool for content acquisition strategy.

 🛠️ Key Technical Features
- Advanced NLP Implemented a custom pipeline with Lemmatization and TF-IDF to vectorize unstructured plot summaries.
- Predictive Excellence: Achieved an **R² score of 0.83 using a Tuned Random Forest Regressor.
- Model Interpretability: Utilized feature importance to identify that TMDB scores and Runtime are the strongest predictors of critical success.

## 🚀 Repository Contents
- `prime_video_analysis.ipynb`: The complete end-to-end data pipeline.
- `prime_video_model.joblib`: The serialized champion model ready for deployment.
- `LICENSE`: Open-source MIT license.

## 📈 Future Roadmap
- Transitioning to BERT Transformers for deeper semantic analysis.
- Integrating a "Star Power" index for cast/crew contribution analysis.
