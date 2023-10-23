# Summarisation-of-Text-Using-Natural-Language-Processing

This is a Python script that performs text summarization and generates a PowerPoint presentation based on the summarized text. It uses the `sumy` library for text summarization and the `python-pptx` library for PowerPoint generation.

## Requirements

Before running the script, make sure you have the following libraries and dependencies installed:

- `sumy`
- `nltk`
- `python-pptx`
- Google Drive API Client

You can install these dependencies using `pip`:

```bash
pip install sumy nltk python-pptx
```

Additionally, you need to download NLTK data:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')
nltk.download('maxent_ne_chunker')
nltk.download('words')
```

## Usage

1. **Authentication**: Authenticate your Google account to access the document using the `auth.authenticate_user()` method.

2. **Google Drive Document**: Provide the Google Drive document's file ID in the `doc_file_id` variable.

3. **Running the Script**: Execute the script to fetch the content of the document, perform summarization, and generate a PowerPoint presentation.

```python
python your_script_name.py
```

## Output

The script will generate a PowerPoint presentation with the summarized content and save it as `SummarizationPresentation.pptx`.

