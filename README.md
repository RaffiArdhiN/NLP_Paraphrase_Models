# NLP_Paraphrase_Models

This repository focuses on implementing various machine learning models for paraphrase tasks in Natural Language Processing (NLP) using the Quora Paraphrasing dataset in Indonesian.

## Description

Paraphrasing is the process of rephrasing a text with different words without altering its meaning. In NLP, paraphrasing is used to enhance a machine's understanding of language variations. This repository explores several model architectures for paraphrasing tasks, including:

- **Recurrent Neural Network (RNN)**: A sequential model capable of capturing temporal dependencies in text data.
- **Long Short-Term Memory (LSTM)**: A variant of RNN designed to address the vanishing gradient problem by introducing long-term memory mechanisms.
- **Transformer**: A model architecture that relies on self-attention mechanisms to process sequential data, enabling parallel processing and capturing long-range dependencies in text.

## Dataset

The dataset used is the [Quora Paraphrasing Dataset Indonesian Version](https://github.com/louisowen6/quora_paraphrasing_id), containing pairs of questions from Quora translated into Indonesian. It consists of over 150,000 pairs of questions labeled as duplicates.

## Repository Structure

- `ID_Quora_Paraphrasing_train.csv`: Training dataset used for model training.
- `NLP_Paraphrase_RNN.ipynb`: Notebook implementing the RNN model for paraphrasing tasks.
- `NLP_Paraphrase_LSTM.ipynb`: Notebook implementing the LSTM model for paraphrasing tasks.
- `NLP_Paraphrase_Transformer.ipynb`: Notebook implementing the Transformer model for paraphrasing tasks.
- `Final_Task_1.ipynb`, `Final_Task_2.ipynb`, `Final_Task_3.ipynb`: Additional notebooks containing experiments and analyses related to paraphrasing tasks.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/RaffiArdhiN/Paraphrase-Repo-NLP.git
   cd Paraphrase-Repo-NLP
   ```

2. **Create and activate a virtual environment** (optional but recommended):

   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/Mac
   env\Scripts\activate  # For Windows
   ```

3. **Install dependencies**:

   Ensure you have the latest version of `pip`, then run:

   ```bash
   pip install -r requirements.txt
   ```

   *Note*: If the `requirements.txt` file is not available, create one by listing all necessary libraries, such as `pandas`, `numpy`, `scikit-learn`, and Hugging Face's `transformers`.

## Usage

After installation, you can run the available notebooks to train and evaluate the paraphrasing models. Each notebook includes step-by-step explanations of the training and evaluation process.

## Contribution

Contributions are highly welcome. Feel free to fork this repository and submit a pull request to suggest improvements or add new features.

## License

This repository is licensed under the [MIT License](LICENSE).

## References

- [Quora Paraphrasing Dataset Indonesian Version](https://github.com/louisowen6/quora_paraphrasing_id)
- [NLP Indonesian Resources](https://github.com/irfnrdh/Awesome-Indonesia-NLP)
