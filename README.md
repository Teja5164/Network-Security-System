# Network Security System – ML-based Intrusion Detection & Cloud Deployment

**Technologies:** Python, scikit-learn, FastAPI, AWS, Azure  

An end-to-end **Machine Learning-driven Intrusion Detection System (IDS)** that detects malicious network activity using structured logs. The system is deployed on cloud platforms (AWS and Azure) and designed for scalability with CI-ready architecture.

---

## Features

- **ML-driven detection:** Trains models on structured network logs to identify potential security threats.
- **Complete pipeline:** Includes data ingestion, cleaning, exploratory data analysis (EDA), feature engineering, and model training.
- **Exception-logged architecture:** Ensures robust and traceable system behavior.
- **Hyperparameter tuning:** Optimized for better accuracy and detection performance.
- **FastAPI deployment:** Serves the prediction API for real-time intrusion detection.
- **Cloud deployment:** Easily deployable on AWS Elastic Beanstalk, EC2, and Azure Web App.

---

## Project Structure

```

network-security-ml/
├── data/               # Dataset or sample logs
├── notebooks/          # EDA and model experimentation
├── src/                # Source code for data processing and model training
├── app/                # FastAPI application
├── requirements.txt    # Python dependencies
├── README.md
└── .gitignore

````

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/network-security-ml.git
cd network-security-ml
````

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

---

## Usage

### Train the Model

```bash
python src/train_model.py
```

### Run FastAPI Server

```bash
uvicorn app.main:app --reload
```

* Access the API at: `http://127.0.0.1:8000/docs`

---

## Deployment

* **AWS:** Elastic Beanstalk, EC2
* **Azure:** Web App
* Designed with CI-ready project structure for easy cloud deployment.

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License.
