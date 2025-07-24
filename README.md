# Generative Text with GPT-2

This project demonstrates how to generate coherent paragraphs of text using OpenAI's GPT-2 language model with the Hugging Face Transformers library and PyTorch.

## Features

- Loads a pre-trained GPT-2 model and tokenizer.
- Generates text continuations for a list of prompts.
- Supports GPU acceleration (if available).
- Easily customizable for different prompts, output lengths, and creativity (temperature).

## Requirements

- Python 3.7+
- torch
- transformers

Install dependencies with:

```sh
pip install torch transformers
```

## Usage

1. **Clone the repository** and open the notebook or script.

2. **Run the notebook or script**:

   - If using the notebook, run all cells.
   - If using as a script, run:
     ```sh
     python "GENERATIVE TEXT.ipynb"
     ```
     *(You may want to convert the notebook to a `.py` file for command-line use.)*

3. **Output**: The script will print generated paragraphs for each prompt in the list.

## Customization

- **Change Prompts**: Edit the `prompts` list to use your own starting sentences.
- **Adjust Output Length**: Change the `max_length` parameter in `generate_text`.
- **Control Creativity**: Modify the `temperature` parameter (higher = more creative, lower = more deterministic).

## Example

**Prompt:**  
`The future of artificial intelligence will`

**Generated Text:**  
*(Example output will vary each run)*  
`The future of artificial intelligence will continue to evolve as new technologies emerge, enabling machines to learn and adapt to complex environments...`

## References

- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers/index)
- [GPT-2 Paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)

---

**Author:** Tushar Mathur
