# Weather-forecasting
weather-lstm-prediction/
│
├── data/
│   ├── Weather_Data.csv       # Original dataset
│   ├── Processed_Weather_Data.csv  # Processed dataset after cleaning
│
├── models/
│   ├── univariate_lstm.py     # Univariate LSTM model
│   ├── multivariate_lstm.py   # Multivariate LSTM model
│   ├── multi_step_lstm.py     # Multi-step LSTM model
│
├── visualizations/
│   ├── loss_plot.png          # Training/validation loss plot
│   ├── prediction_plot.png    # Actual vs Predicted plot
│
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies
└── train_model.py             # Main script to train LSTM models
