# Data science project analyzing trader behavior vs market sentiment

## 📖 Overview
This project analyzes **trader behavior** in relation to **market sentiment** using two datasets:

1. **Historical Trader Data** – Detailed trade-level data, including trade size, leverage, and profit/loss.
2. **Fear & Greed Index** – Daily market sentiment classifications: Extreme Fear, Fear, Greed, Extreme Greed.

The objective is to **uncover relationships between trading patterns and market sentiment** to guide smarter trading strategies.

---

## 📂 Project Structure
The final project is organized as follows:
```
ds_Rahul/
├── notebook_1.ipynb       # Main Google Colab notebook
├── csv_files/             # Folder for datasets
│   ├── historical_data.csv
│   └── fear_greed_index.csv
├── outputs/               # Generated charts and visualizations
│   ├── buy_vs_sell.png
│   ├── daily_volume.png
│   ├── avg_pnl_by_sentiment.png
│   └── pnl_by_sentiment.png
├── ds_report.pdf          # Final PDF report
└── README.md              # Project documentation
```

> **Note:**  
> The `csv_files/` folder is **empty by default** in this repository.  
> You must **download the datasets separately** (instructions below).

---

## 📥 Download the Datasets

Due to GitHub’s file size restrictions, the CSV files are **not included** in this repository.

Please download them manually from the following links and place them inside the `csv_files/` folder:

| Dataset Name          | Download Link |
|-----------------------|---------------|
| Historical Trader Data | [Download Here](https://drive.google.com/file/d/1IrPIXU4qyHLB_9Vok-83qdbEjl3rQwrL/view?usp=drive_link) |
| Fear & Greed Index     | [Download Here](https://drive.google.com/file/d/1n1MJ6S-8YJ0vw4uaya2bxPiZJjET_fRP/view?usp=drive_link) |

### **Steps to Add Datasets**
1. Download both CSV files from the links above.
2. Create a folder named `csv_files` inside your project root (if not already present).
3. Place:
   - `historical_data.csv`
   - `fear_greed_index.csv`
   
   inside the `csv_files/` folder.
4. Your folder should look like this:

```
ds_Rahul/
├── csv_files/
│ ├── historical_data.csv
│ └── fear_greed_index.csv
```

---

## 📥 Access Notebook & Report

You can directly view and run the notebook in Google Colab, and access the final report:

| File                | Link |
|--------------------|------|
| `notebook_1.ipynb` | [Open in Colab](https://colab.research.google.com/drive/1ffweWvTodeAPr5hdiSMlRIZC8RDEEwmQ?usp=drive_link) |
| `ds_report.pdf`    | [View Report](https://drive.google.com/file/d/1rSrmrUBXrm9Yz7LKS4okZMMi4QDBpHM0/view?usp=drive_link) |

---

## 🚀 How to Run the Project

### **Option 1: Run in Google Colab (Recommended)**
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `notebook_1.ipynb` to Colab or open directly via the link above.
3. Make sure your datasets are available in `csv_files/`.
4. Update the notebook paths if needed:
5. Run all cells step-by-step.

## 📊 Outputs
1. Visualization	-- Description
2. buy_vs_sell.png	-- Buy vs Sell trade count
3. daily_volume.png	-- Daily total trading volume
4. avg_pnl_by_sentiment.png	-- Average profit per trade by sentiment
5. pnl_by_sentiment.png	-- Total profit by sentiment

All generated visualizations will be saved automatically in the outputs/ folder.

## 📝 Deliverables
File	Description
1. notebook_1.ipynb	-- Full code and analysis
2. outputs/	 -- Charts and visualizations
3. ds_report.pdf	  -- Final summarized report
4. README.md	  -- Project instructions and documentation

## 💡 Notes

The analysis will not run unless you download and correctly place the CSV files into the csv_files/ folder.

Check file paths carefully if you encounter issues.

## 📧 Contact

If you have questions about this project, feel free to open an issue or reach out.
