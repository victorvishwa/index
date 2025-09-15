# LLM Annotation Tool

A Streamlit-based tool for annotating LLM-generated text with various quality metrics.

## Project Structure

- `app.py`: Main application file
- `config.py`: Configuration settings and constants
- `data_handler.py`: Data loading and saving operations
- `ui_components.py`: Streamlit UI components
- `requirements.txt`: Project dependencies

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Prepare your input data:
   - Create a CSV file named `eval_tag_input.csv`
   - The CSV should contain at least a 'text' column with the content to annotate

3. Run the application:
```bash
streamlit run app.py
```

## Features

- Annotation interface for multiple quality metrics
- Progress tracking
- Automatic saving of annotations
- Clean and intuitive UI

## Tags

The tool supports the following annotation tags:
- Grammar & Spelling
- Repetition
- Extra Information
- Less Information
- Pure Hindi
- Relevance Choice
- Context Preservation

Each tag can be marked as Pass (1) or Fail (0). 
