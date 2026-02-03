This project implements a GPT-style subword tokenizer using Byte Pair Encoding (BPE).
It is built for efficient text preprocessing and can be used directly in large-scale language model pipelines.

The tokenizer follows byte-level preprocessing and learns subword merge rules from a text corpus, similar to how GPT-family models tokenize text. It supports converting text into tokens and reconstructing text back from tokens.

How to use

Download the file.

Make sure Python 3 is installed.

Run it directly:
```bash
python tokenizer.py
```
If a corpus file is required, place it in the same directory and update the filename inside the script if needed.

The script will:

Train a BPE tokenizer on the given text

Build a subword vocabulary

Encode input text into token IDs

Decode token IDs back into text

No external APIs, no model downloads, and no additional setup required.

This project is intended for learning, experimentation, and custom NLP or LLM preprocessing workflows.

If you want, I can make it even shorter (3–4 lines) or rewrite it to sound more casual / student-project style.
