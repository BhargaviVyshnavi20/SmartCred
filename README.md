# SmartCred

A credit risk assessment platform with ML-powered credit scoring, built with FastAPI backend and React frontend.

## Features

- **ML-Powered Credit Scoring**: Uses trained ML model for accurate credit score predictions (300-900 range)
- **User Dashboard**: Track credit applications and score history with analytics
- **Admin Portal**: Comprehensive analytics with interactive charts and application management
## Tech Stack

**Backend:**
- FastAPI
- SQLite
- scikit-learn (ML model)
- Python 3.x

**Frontend:**
- React
- React Router
- CSS3 with gradients and animations

## Installation

### Prerequisites
- Python 3.8+
- Node.js 14+
- npm or yarn

### Backend Setup

1. Navigate to backend directory:
```bash
cd backend
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Populate sample data (optional):
```bash
python populate_sample_data.py
```

4. Start the FastAPI server:
```bash
python -m uvicorn main:app --reload
```

The backend will run on `http://localhost:8000`

### Frontend Setup

1. Navigate to frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The frontend will run on `http://localhost:3000`
