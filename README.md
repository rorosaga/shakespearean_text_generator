# Shakespearean Text Generator 📝 ✍️

<p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=yellow" />
    <img alt="NLTK" src="https://img.shields.io/badge/NLTK-154F5B?style=for-the-badge&logo=python&logoColor=white" />
    <img alt="Numpy" src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" />
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" />
   
</p>


NLP text generation model that works with 2/3/4-grams to imitate the style of Shakespeare's writing, based on the probabilities of the next most likely token.

## Overview 🌠

1. Analyzes three Shakespeare plays (Julius Caesar, Hamlet, and Macbeth)
2. Builds probability distributions of word sequences
3. Generates new text based on these distributions

## Dataset 📚

The project uses three Shakespeare plays from the NLTK corpus:
- **Julius Caesar**
- **Hamlet**
- **Macbeth**

## Installation 🛠️

### Prerequisites 📦

- Python 3.x
- NLTK
- Numpy
- Jupyter Notebook

### Steps 📋

1. Clone the repository and navigate to the project directory.

```bash
git clone https://github.com/rorosaga/shakespearean_text_generator.git
```
```bash
cd shakespearean_text_generator
```

2. Create the virtual environment and activate it.

```bash
python -m venv .venv
```
> **Windows**
```bash
source .venv\Scripts\activate
```
> **MacOS/Linux**
```bash
source .venv/bin/activate
```


3. Install dependencies.

```bash
pip install -r requirements.txt
```

4. Run all cells in the jupyter notebook!! 🏃‍➡️

## Results 📊

The model shows different characteristics based on n-gram size:

### 2-grams
- Produces fragmented, less coherent text
- Captures basic word pairs but lacks broader context

### 3-grams
- Improved coherence over 2-grams
- Better phrase structure but still some inconsistencies

### 4-grams
- Best coherence and fluency
- Successfully reproduces famous Shakespearean phrases
- Most natural-sounding output

## Testing 🧪

The project includes comprehensive unit tests for all components:
- Text preprocessing
- N-gram generation
- Token counting
- Probability calculations
- Text generation


