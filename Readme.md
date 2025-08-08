project-root/
│
├── airflow/
│   ├── dags/
│   ├── Dockerfile
│   └── docker-compose.yaml  ← Airflow-only services
│
├── mlflow/
│   ├── Dockerfile
│   ├── mlruns/              ← Local MLflow experiment tracking
│   └── docker-compose.yaml  ← MLflow-only services
│
├── fastapi/
│   ├── models/
│   ├── src/
│   ├── Dockerfile
│   └── requirements.txt
│
├── shared/                  ← Optional: shared volumes like data or models
│   └── models/
│
├── .dockerignore
└── README.md
