# Text Classification and Similarity Web Application

This project is a web-based text classification and similarity prediction application using a fine-tuned Sentence Transformer model. Users can input a sentence, and the application will predict the label for classification (either "Label 0" or "Label 1") and provide accuracy metrics. The application also displays a classification report for detailed analysis.

## Project Structure

The project structure is organized as follows:

- `app.py`: The main Flask application file for running the web server and handling user input.
- `model/fine_tuned_model`: The directory where the fine-tuned Sentence Transformer model is stored.
- `data/raw`: The directory for storing raw training and test data in CSV format.
- `templates`: The directory for HTML templates used for the web interface.
  - `index.html`: The HTML template for the user interface.
- `requirements.txt`: A file listing the required Python packages and their versions.
- `results`: A directory for storing result files, such as cosine similarity scores.
- `static`: A directory for storing static assets, if needed.
  
## Usage

1. Install the required packages by running the following command:
   ```bash
   pip install -r requirements.txt
