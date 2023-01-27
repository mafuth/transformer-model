# Basic Generative Pre-trained Transformer Model
## Goal of this model is text completion

Install tokenizer used in GPT3
```
pip install tiktoken
```
Example usage of tiktoken
```python
import tiktoken
enc = tiktoken.get_encoding("gpt2")

"""Returning the number of tokens in a text string."""
assert enc.decode(enc.encode("hello world")) == "hello world"

"""Returning the original string from tokens"""
encoding.decode([83, 1134, 30001, 318, 1049, 0])
```

Trainnig data:
[OPENWEB DATA](https://drive.google.com/file/d/1EA5V0oetDCOke7afsktL_JDQ-ETtNOvx/view?usp=share_link)
