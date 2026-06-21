# Utku Ulu

AI Engineer at BosphorusISS in Istanbul, where I have spent the last two years building applied
machine learning for industry: computer vision, local LLM systems, and predictive models, taken
from research through to production and a real interface.

The work runs at a systems level, not wrapper code over an AI API. I train models that solve a
concrete problem, then own everything around them: serving, retraining, the API, and the UI.

## Focus

- Computer vision: custom YOLO pipelines for real-time quality inspection and threat detection,
  with retraining loops that keep them current, plus OCR and face detection.
- LLMs and RAG: fully local retrieval-augmented systems running on GPU over custom datasets, with no
  dependence on external APIs, including Model Context Protocol (MCP) integrations.
- Forecasting and tabular ML: LSTM predictive-maintenance models on real factory data,
  gradient-boosted trees (XGBoost), and calibrated ensembles with proper backtesting and honest
  uncertainty.
- Production: FastAPI, Streamlit and Next.js services, packaging, model versioning, and CI.

## Selected work

[World Cup Forecaster](https://github.com/uluutku/world-cup-forecaster) is a probabilistic football
forecasting system that never looks at the future. It builds every feature in date order, blends
three calibrated models (logistic regression, gradient boosting, and a Dixon-Coles goals model),
backtests across five World Cups, and froze its 2026 predictions before kickoff. Served through a
Streamlit dashboard and a FastAPI API. Built with Python, scikit-learn, FastAPI, and Streamlit.

Most of my computer vision and LLM work is built at BosphorusISS, so those repositories are private.

## Stack

Python, PyTorch, scikit-learn, XGBoost, YOLO, OpenCV, FastAPI, Streamlit, with React and Next.js for
the interfaces that ship alongside the models.

## Side projects

RabbitWiz ([rabbitwiz.com](https://rabbitwiz.com)) is a small family of web and mobile apps I build
under one brand. One of them, [PawPicker](https://play.google.com/store/apps/details?id=com.pawpicker),
is live on Google Play.

## Contact

[LinkedIn](https://www.linkedin.com/in/utkuulu/), [Email](mailto:utkuulu01@gmail.com), [GitHub](https://github.com/uluutku), [rabbitwiz.com](https://rabbitwiz.com)
