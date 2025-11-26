# skin-cancer-detection-ai
Skin cancer classification using EfficientNet-B3 trained on HAM10000 dataset. Uses transfer learning for faster convergence and high accuracy across 7 lesion types. Includes training pipeline, results, Grad-CAM visualization for explainability, and confusion/ROC evaluation.


EfficientNet-B3 based classification model

Transfer Learning for high accuracy & fast training

Grad-CAM support for visual explainability

Confusion Matrix, Accuracy & ROC evaluation

Full-stack Web Interface

Live prediction from uploaded images



```
skin-lesion-efficientnetb3/
│── backend/
│   ├── app.py                 # FastAPI backend server
│   ├── uploads/               # Uploaded lesion images
│   ├── requirements.txt       # Backend python dependencies
│
│── frontend/                  # React frontend (Vite + Tailwind)
│   ├── src/                   # UI + Components
│   ├── public/
│   ├── package.json
│
│── logs/                      # Model logs + metrics
│── data/                      # Dataset storage (optional)
│── scripts/                   # Helper python scripts
│── configs/                   # Model configs (e.g., config.yaml)
│── notebooks/                 # Experiments & EDA notebooks
│── uploads/                   # Prediction output storage
│── requirements.txt           # Root dependency file (optional)
│── LICENSE
│── README.md 
```

```
git clone <repo-url>
cd skin-lesion-efficientnetb3
```


```
cd backend
pip install -r requirements.txt
uvicorn backend.app:app --reload
```

```
cd frontend
npm install
npm run dev
```



