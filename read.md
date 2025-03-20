# Step 1: Navigate to your project directory
cd C:\Users\Text_Emotion_Detection

# Step 2: Create a virtual environment (if not already created)
python -m venv venv

# Step 3: Activate the virtual environment
.\venv\Scripts\activate

# Step 4: Install the required dependencies
pip install streamlit pandas numpy altair joblib scikit-learn

# Step 5: Run the Streamlit app
streamlit run app.py
