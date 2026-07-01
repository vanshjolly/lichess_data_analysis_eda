# ♟️ Lichess Chess Games - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Lichess Chess Games Dataset** to uncover meaningful insights about player ratings, game outcomes, openings, time controls, and game duration.

The analysis includes:
- Data Cleaning
- Data Preprocessing
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Business Insights
- Visualizations

The project is implemented using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 📂 Dataset Information

The dataset contains approximately **20,000 chess games** played on the Lichess platform.

### Features

| Column | Description |
|----------|-------------|
| id | Unique Game ID |
| rated | Rated or Casual Game |
| created_at | Game Creation Time |
| last_move_at | Last Move Timestamp |
| turns | Number of Turns |
| victory_status | How the Game Ended |
| winner | Winner of the Game |
| increment_code | Time Control |
| white_rating | White Player Rating |
| black_rating | Black Player Rating |
| opening_name | Chess Opening Name |
| opening_eco | ECO Code |
| opening_ply | Opening Depth |

---



# 📈 Key Insights

- White wins slightly more games than Black.
- Most players belong to the intermediate rating range.
- Players are generally matched with opponents having similar ratings.
- Games between similarly rated players tend to be more competitive.
- Popular openings dominate competitive games.
- Time control influences the average game length.

---

# 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/lichess-eda.git
```

Move into the project directory

```bash
cd lichess-eda
```

Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

---

# ▶️ How to Run the Project

### Step 1

Clone or download the repository.

### Step 2

Install all required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 3

Place the dataset (`games.csv`) inside the project folder.

Example structure:

```
Lichess-EDA/
│
├── games.csv
├── lichess_data_analysis.ipynb
├── README.md
```

### Step 4

Open the notebook using either:

- Jupyter Notebook

```bash
jupyter notebook
```

or

- Google Colab

Upload the notebook and dataset.

### Step 5

Run all notebook cells from top to bottom.

---

# 📁 Project Structure

```
Lichess-EDA
│
├── games.csv
├── lichess_data_analysis.ipynb
├── README.md
├── images/
└── requirements.txt (optional)
```

---

# 📊 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```


# 👨‍💻 Author

**Vansh Jolly**

B.Tech Electronics & Communication Engineering

---

