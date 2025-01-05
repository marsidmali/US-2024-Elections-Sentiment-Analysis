# 📊 US Elections 2024 Reddit Sentiment Analysis

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A project analyzing public sentiment around Kamala Harris and Donald Trump during the 2024 US Presidential Election using Reddit data.

## ✨ Features

- 🤖 **Advanced NLP**: Utilizes RoBERTa-based model for accurate sentiment classification
- 📱 **Social Media Mining**: Extracts and analyzes Reddit comments using PRAW
- 📊 **Rich Visualizations**: Includes temporal trends, word clouds, and sentiment distributions
- 🔍 **Comprehensive Analysis**: Covers both candidate-specific and comparative insights
- 📈 **Time Series Analysis**: Tracks sentiment evolution throughout the election period

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/marsidmali/us-2024-elections-sentiment-analysis.git
cd us-elections-sentiment-analysis
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Add your Reddit API credentials

## 🚀 Usage

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `us_2024_elections_reddit_sentiment_analysis.ipynb`
3. Run all cells to perform the analysis


## ⚙️ Configuration

Create a `.env` file with your Reddit API credentials:
```plaintext
REDDIT_CLIENT_ID=your_client_id_here
REDDIT_CLIENT_SECRET=your_client_secret_here
REDDIT_USER_AGENT=your_user_agent_here
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/marsidmali/US-2024-Elections-Sentiment-Analysis/blob/main/LICENSE) file for details.





