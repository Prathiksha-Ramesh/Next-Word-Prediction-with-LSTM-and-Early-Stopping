# Next Word Prediction with LSTM and Early Stopping

This project demonstrates a machine learning application using a Long Short-Term Memory (LSTM) model to predict the next word based on a given sequence of words. It features a simple user interface built with Streamlit that allows users to input a sequence and receive predictions interactively.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Dependencies](#dependencies)
- [License](#license)
- [Contributing](#contributing)

## Features

- Predict the next word in a sequence using a pre-trained LSTM model.
- Interactive user interface using Streamlit for real-time predictions.

## Installation

1. **Clone the repository**:

``` bash
git clone https://github.com/yourusername/next-word-prediction.git cd next-word-prediction
```


2. **Set up a Python environment** (recommended):
``` bash 
python -m venv env source env/bin/activate # Use env\Scripts\activate on Windows
``` 

3. **Install dependencies**:
``` bash
pip install -r requirements.txt
```


## Usage

Run the Streamlit application:
``` bash
streamlit run app.py
```

Navigate to `localhost:8501` in your web browser to interact with the application.

## Project Structure

- `app.py`: Streamlit application frontend.
- `next_word_lstm.h5`: Pre-trained LSTM model.
- `tokenizer.pickle`: Tokenizer for encoding text sequences.
- `requirements.txt`: List of dependencies.

## How It Works

The application uses a tokenizer to convert input text sequences into tokens, which are then padded and fed into the LSTM model to predict the next word. The predicted word is then displayed on the Streamlit interface.

## Dependencies

- numpy
- tensorflow
- streamlit
- pickle  # Ensure all dependencies are correctly listed in `requirements.txt`

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request with your suggestions.
