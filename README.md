## 🚀 Quick Start

### Prerequisites
- Visual Studio 2022
- Python 3.11+
- .NET 8 SDK
- SQL Server

## 📁 Project Structure
ihs-towers-mvp/
├── backend-python/     # FastAPI + ML services
├── backend-dotnet/     # .NET Core Web API
├── infrastructure/     # Azure deployment
└── docs/              # Documentation

## 🛠️ Tech Stack
- **Backend**: Python (FastAPI), .NET Core (ASP.NET Web API)
- **Database**: SQL Server with Entity Framework Core
- **AI/ML**: scikit-learn, pandas (revenue prediction & analytics)
- **Cloud**: Microsoft Azure (deployment ready)

## 🎯 Key Features
- 📊 **Revenue Prediction** - ML models for tower income forecasting
- 🔍 **Performance Analytics** - Real-time tower monitoring
- 🏗️ **Tower Management** - Complete CRUD operations
- 🤖 **Anomaly Detection** - Automated issue identification
- 📱 **RESTful APIs** - Swagger documentation included

### Run Locally
```bash
# Python API
cd backend-python
pip install -r requirements.txt
python src/main.py  # http://localhost:8000

# .NET API  
cd backend-dotnet
dotnet run --project TowerManagement.Api  # https://localhost:7XXX
