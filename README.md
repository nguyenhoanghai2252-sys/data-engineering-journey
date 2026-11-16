data-engineering-journey/
├── README.md                  # Bảng điều khiển tiến độ tổng (32 tuần) + Liên kết nhanh
├── .gitignore                 # Bỏ qua venv/, __pycache__/, .env, file dữ liệu lớn (*.csv, *.parquet)
├── assets/                    # Nơi lưu trữ toàn bộ sơ đồ kiến trúc (Excalidraw/Eraser/PNG)
│   ├── week01-02_etl_flow.png
│   └── ...
├── phase-1-foundations/       # Giai đoạn 1: Python, SQL, Docker, API (Tuần 1 - 8)
│   ├── week-01-python-basics/
│   │   ├── README.md          # Tóm tắt kiến thức tuần 1 + Hình minh họa luồng code
│   │   ├── day01_variables.py
│   │   └── mini_lab_transactions.py
│   ├── week-02-file-handling/
│   │   ├── README.md
│   │   ├── src/
│   │   │   └── clean_data.py
│   │   ├── sample_data/       # Chỉ để file mẫu nhỏ (~20 dòng) để người khác chạy thử
│   │   └── requirements.txt
│   ├── week-03-04-sql/
│   └── ...
├── phase-2-dwh-modeling/      # Giai đoạn 2: Data Modeling, BigQuery, dbt (Tuần 9 - 14)
├── phase-3-orchestration/     # Giai đoạn 3: Airflow, PySpark, Kafka (Tuần 15 - 22)
└── phase-4-ai-data-pipeline/  # Giai đoạn 4: Unstructured Data, Vector DB, RAG (Tuần 23 - 32)
