# QuantAlgo Trading System

Algorithmic trading system for Angel One broker using Python and FastAPI.

## 🚀 Quick Start

1. **Clone & Setup**
```bash
git clone https://github.com/QuantAlgoAI/QuantAlgoAI.git
cd QuantAlgoAI
python -m venv ~/quantalgo_venv
source ~/quantalgo_venv/bin/activate  # Windows: ~/quantalgo_venv/Scripts/activate
pip install -r requirements.txt
```

2. **Configure**
```bash
cp .env.example .env
# Edit .env with your credentials
```

3. **Start Services**
```bash
docker-compose up -d
```

4. **Run Application**
```bash
cd backend
python run.py
```

## 📊 Features

- Angel One API Integration
- Real-time Market Data
- Automated Trading Strategies
- Risk Management
- Telegram Notifications
- Email Alerts

## 🛠️ Development

```bash
# Run tests
pytest backend/tests/

# Check setup
./scripts/test_ci.sh

# Build containers
docker-compose build
```

## 📝 License

MIT License - see [LICENSE](LICENSE)
