# Deployment Plan

High-level plan:

1. Export trained model (joblib / pickle) and a prediction API (FastAPI / Flask).
2. Create a small dashboard for visa officers to view model predictions and explanation (feature contributions).
3. Build a periodic retraining pipeline with monitoring for data drift and performance metrics.
4. Start with a shadow deployment or pilot before full automated decision-making — keep human-in-the-loop.
