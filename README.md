```markdown
# 🚦 Network Protocol Simulator & Analyzer
This project simulates core networking protocol behavior using Python, with a focus on Stop-and-Wait ARQ and congestion effects. It visualizes round-trip time (RTT) and packet drops using synthetic transmission data. Designed for demonstrating basic networking logic and protocol analysis.
## 🔧 Features
- Implements Stop-and-Wait ARQ logic
- Simulates packet loss and delay
- Visualizes RTT across packet transmissions
- Introduces networking concepts like reliability and retransmission
## 📦 Technologies Used
- Python 3
- Matplotlib
- Random
- Google Colab / Jupyter Notebook
## ▶️ How to Run
1. Open the `.ipynb` file in Google Colab or Jupyter.
2. Run all cells to simulate and visualize packet behavior.
3. Packet drops and RTTs will be printed and plotted live.
## 📁 Simulation Parameters
- Number of packets: 20
- Drop rate: 20%
- RTT range: 0.1s to 0.4s (for successful packets)
## ⚠️ Notes
- Uses synthetic delays and loss to simulate real-world congestion.
- Not connected to real network interfaces.
- Can be extended with other ARQ protocols or variable drop models.
## 📌 Status
✅ Fully working simulation  
📊 Enhancements planned: Go-Back-N, Selective Repeat, interactive graphs
```
