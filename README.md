# Bike Sharing Database Dahboard
## Prerequisites
- Python 3.x
- Streamlit
- Pandas
- Matplotlib
- Seaborn

## Installation
1. Clone the repository or download the code.
2. Install the required packages:
   ```bash
   pip install streamlit pandas matplotlib seaborn

## Running the Dashboard
To run the Streamlit dashboard, follow these steps:
```bash
# Step 1: Install Streamlit
!pip install streamlit

# Step 2: Mount Google Drive
from google.colab import drive
drive.mount('/content/drive')

# Step 3: Run the Dashboard with Localtunnel
!streamlit run dashboard.py & npx localtunnel --port 8501

# Step 4: After running the command, look for the URL provided by Localtunnel. This URL will allow you to view your dashboard in a new tab.
