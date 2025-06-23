# Titanic Data Preprocessing

## 🛠️ Preprocessing Steps
1. Dropped `Cabin` column (77% missing)
2. Filled missing values:
   - `Age`: Median
   - `Embarked`: Mode
3. Encoded categorical features:
   - `Sex`: Label Encoding (male=1, female=0)
   - `Embarked`: One-Hot Encoding
4. Scaled numerical features (`StandardScaler`)
## 🔍 Outlier Treatment  
- Visualized using boxplots

## 📂 File Structure
titanic-data-preprocessing/
├── data/
│ ├── raw/titanic.csv # Original data
│ └── processed/ # Cleaned data
├── notebooks/ # Jupyter notebook
└── scripts/ # Python scripts


## 🚀 Usage
```bash
# Run preprocessing
python scripts/preprocess.py

# Or open notebook:
jupyter notebook notebooks/titanic_preprocessing.ipynb


Then push it:
```bash
git add README.md
git commit -m "Added project README"
git push
