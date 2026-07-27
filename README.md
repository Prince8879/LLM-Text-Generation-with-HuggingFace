# Text Generation using Pre-trained Large Language Models (LLMs)

A Natural Language Processing (NLP) project demonstrating text generation using pre-trained Large Language Models (LLMs) from the Hugging Face Transformers library.

This project allows users to generate different types of text, including stories, technical explanations, and question-answer responses while experimenting with various text generation parameters.

---

## Project Objective

The objective of this project is to explore text generation using pre-trained language models and understand how different generation parameters influence the quality, diversity, and creativity of generated text.

---

## Features

- Load different pre-trained Hugging Face language models
- Story Generation
- Technical Explanation Generation
- Question & Answer Generation
- Custom user prompts
- Adjustable generation parameters:
  - Temperature
  - Maximum Length
  - Top-K Sampling
  - Top-P (Nucleus Sampling)
- Compare outputs using different parameter settings

---

## Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- PyTorch

---

## Supported Models

You can use any compatible Hugging Face text generation model, such as:

- GPT-2
- DistilGPT2
- EleutherAI/gpt-neo-125M

---

## Repository Structure

```
Text-Generation-Using-Pretrained-LLM/
│
├── Assignment2_Text_Generation.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── generated_outputs/
│   ├── story_output.txt
│   ├── technical_output.txt
│   ├── qa_output.txt
│   └── parameter_comparison.md
│
└── screenshots/
    ├── story_generation.png
    ├── technical_explanation.png
    ├── qa_generation.png
    └── comparison.png
```

---

## Installation

Clone this repository

```bash
git clone https://github.com/your-username/Text-Generation-Using-Pretrained-LLM.git
```

Move into the project folder

```bash
cd Text-Generation-Using-Pretrained-LLM
```

Install the required libraries

```bash
pip install -r requirements.txt
```

---

## Required Libraries

```
transformers
torch
accelerate
sentencepiece
```

---

## How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Choose a pre-trained model.
4. Select one of the following tasks:
   - Story Generation
   - Technical Explanation
   - Question & Answer
5. Enter the required prompt.
6. Set the generation parameters.
7. Run the notebook to generate text.

---

## Generation Parameters

| Parameter | Description |
|-----------|-------------|
| Temperature | Controls randomness and creativity |
| Max Length | Maximum number of generated tokens |
| Top-K | Limits candidate words to the top K choices |
| Top-P | Uses nucleus sampling for more natural text generation |

---

## Example Tasks

### Story Generation

**Prompt**

```
Once upon a time in a magical forest...
```

---

### Technical Explanation

**Prompt**

```
Explain Cloud Computing in simple terms.
```

---

### Question & Answer

**Prompt**

```
Question:
What is Artificial Intelligence?

Answer:
```

---

## Parameter Comparison

| Experiment | Temperature | Max Length | Top-K | Top-P | Expected Behavior |
|------------|------------|------------|--------|--------|-------------------|
| Experiment 1 | 0.3 | 80 | 20 | 0.80 | More focused and deterministic |
| Experiment 2 | 0.7 | 100 | 50 | 0.90 | Balanced creativity |
| Experiment 3 | 1.0 | 150 | 100 | 0.95 | Highly creative and diverse |

---

## Learning Outcomes

Through this project, you will learn:

- How pre-trained language models work
- Using Hugging Face Transformers
- Text generation using pipelines
- Prompt engineering basics
- Effects of temperature, top-k, top-p, and max_length
- Comparing generated outputs

---

## Future Improvements

- Streamlit Web Application
- Gradio Interface
- Support for Llama Models
- Support for Mistral Models
- Multiple response generation
- Save outputs automatically
- Interactive GUI

---

## References

- Hugging Face Transformers Documentation
- Hugging Face Model Hub
- PyTorch Documentation

---

## Author

**Prince Tiwari**

B.Tech Student | Aspiring DevOps Engineer | AI & Cloud Computing Enthusiast

---

## License

This project is licensed under the MIT License.
