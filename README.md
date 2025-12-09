# Tiny-gpt-from-scratch
“My implementation of a Tiny GPT transformer from scratch using PyTorch.”

🚀 Tiny GPT: Transformer Model Built From Scratch

A minimal GPT-like model implemented using PyTorch

This project is my hands-on implementation of a Tiny GPT Transformer, inspired by Andrej Karpathy’s “Let’s Build GPT” tutorial.
Before this, I covered the theory of LLMs & Transformers through CampusX’s YouTube series — and this project helped me convert that theory into real, working code.

🎯 Features

Fully functional char-level GPT transformer

Built completely from scratch using PyTorch

Implements:

Token & positional embeddings

Multi-Head Self-Attention

Feed-Forward layers

Transformer blocks

Autoregressive text generation

Trained on Tiny Shakespeare dataset

Works on Google Colab GPU

Supports prompt-based text generation

🧠 What I Learned

  How transformers process text token-by-token
  
  How attention actually operates behind the scenes
  
  Difference between training vs inference
  
  How GPT models generate the next token
  
  How theoretical concepts from CampusX translate into working code

📦 Installation
  git clone https://github.com/tushar-gupta525/Tiny-gpt-from-scratch
  cd tiny-gpt-from-scratch
  pip install -r requirements.txt

🏋️ Training the Model

Open the notebook:

  project_gpt.ipynb


  and run all cells (GPU recommended).

✍️ Generating Text

  Use the prompt-based generation section inside the notebook:
  
  print(generate_from_prompt("ROMEO:", max_new_tokens=200))

🔮 Future Work

  Switch from char-level to BPE tokenizer
  
  Train on custom datasets
  
  Increase model size
  
  Add chat-style conversation mode
  
  Explore CampusX’s Generative AI series next

📌 Acknowledgements

  Andrej Karpathy – for the amazing “Build GPT” tutorial
  
  CampusX – for clear explanations on Transformers & LLMs

🙌 Contributions

Feel free to open issues or pull requests!

⭐ Star this repo if you learned something!
