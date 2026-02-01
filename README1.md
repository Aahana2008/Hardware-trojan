# 🔐 Hardware Trojan Detection Platform



An advanced platform for detecting hardware trojans in Verilog RTL designs using hybrid Graph Neural Networks (GNN) and statistical analysis.

## 🚀 Features

- **Hybrid Detection**: Combines GNN (60%) + Statistical Analysis (40%)
- **Interactive Visualizations**: Signal dependency graphs, anomaly detection charts
- **Batch Processing**: Analyze multiple Verilog files simultaneously
- **Detailed Reports**: JSON and CSV export capabilities
- **Real-time Analysis**: Instant feedback with confidence scores

## 📊 Detection Methods

1. **GNN-based Detection**: Graph Attention Networks analyze circuit structure
2. **Statistical Analysis**: Rule-based anomaly detection
3. **Weighted Fusion**: Optimal combination of both approaches

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **ML Framework**: PyTorch, PyTorch Geometric
- **Visualization**: Plotly, NetworkX
- **Data Processing**: NumPy, Pandas, SciPy

## 📦 Installation

### Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/hardware-trojan-detection.git
cd hardware-trojan-detection

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run hardware_trojan_platform.py
```

### Streamlit Cloud Deployment

1. Fork this repository to your GitHub account
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Click "New app"
4. Select your repository, branch, and main file: `hardware_trojan_platform.py`
5. Click "Deploy"!

## 🎯 Usage

1. **Upload Files**: Upload one or more Verilog (.v) files
2. **Select Method**: Choose detection approach (Hybrid, GNN-only, or Statistical-only)
3. **Analyze**: Click "🔍 Analyze Designs" to start detection
4. **Review Results**: Examine detailed reports, visualizations, and anomalies
5. **Export**: Download JSON or CSV reports

## 📈 Detection Metrics

- **Overall Confidence**: Combined probability of trojan presence
- **GNN Score**: Graph-based pattern recognition score
- **Statistical Score**: Rule-based anomaly score
- **Hybrid Score**: Weighted fusion (0.6 × GNN + 0.4 × Statistical)

## 🔍 Anomaly Categories

- Suspicious signal names
- Unusual bit widths
- High fan-out connections
- Isolated signals
- Complex logic patterns
- Rare/counter signals

## 📄 Example Output

```json
{
  "filename": "test_design.v",
  "prediction": "HT-infested",
  "confidence": 0.87,
  "hybrid_score": 0.65,
  "gnn_score": 0.72,
  "statistical_score": 0.54
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is part of the IIT Kanpur Hardware Security Bootcamp 2026.

## 🏆 Competition Details

Developed for the IIT Kanpur Hardware Security Bootcamp focusing on RTL-level hardware trojan detection using modern machine learning techniques.

## 📧 Contact

For questions or issues, please open an issue on GitHub.

---

**Built with ❤️ for Hardware Security**
