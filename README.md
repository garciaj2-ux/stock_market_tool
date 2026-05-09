# Stock Market Trading Tool

Hybrid trading algorithm (LSTM + Evidential Reasoning + BRB) with paper trading integration via Alpaca Markets.

## Quick Start

```bash
python3 -m venv venv
source venv/bin/activate
pip install numpy pandas alpaca-py flask apscheduler python-dotenv

cp .env.example .env
# Edit .env with your Alpaca API keys

python paper_trading_integration.py --mode alpaca
```

## Files

- `paper_trading_integration.py` - Alpaca integration + kill switch
- `hybrid_trading_algorithm.py` - Core trading algorithm
- `.env.example` - Configuration template

## Documentation

See `/Documentation` folder for:
- MODE_A_SETUP.md - Step-by-step Mode A setup
- KILL_SWITCH_README.md - Pause/resume control
- QUICKSTART.md - Quick start guide
