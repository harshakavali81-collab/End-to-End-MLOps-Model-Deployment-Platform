# End-to-End MLOps Model Deployment Platform — implementation

Data input → validation → train/test split → baseline models → error analysis and metrics → model serialization → FastAPI prediction → unit tests.

Run `python engine.py train`; then `python -m unittest discover -s tests -v`. Serve locally using `uvicorn api:app --reload`.

**Limitation:** This is a local release, test and drift demonstration; no actual MLflow registry, public cloud deployment or automated retraining.
