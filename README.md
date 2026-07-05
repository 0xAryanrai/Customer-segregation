# Customer-segregation
# Parcl Buyer Segmentation — Setup

1. Put `clients.csv`, `properties.csv`, `buyer_segmentation_analysis.ipynb`, and `streamlit_app.py` in the same folder.
2. Install dependencies:
   ```
   pip install pandas numpy scikit-learn scipy matplotlib seaborn plotly streamlit jupyter
   ```
3. **Notebook (EDA + modeling):** `jupyter notebook buyer_segmentation_analysis.ipynb`
4. **Dashboard (live app):** `streamlit run streamlit_app.py`
   - Opens at http://localhost:8501
   - If clients.csv/properties.csv aren't found next to the script, use the sidebar file uploaders.
   - Adjust the cluster count (k) live with the sidebar slider.
