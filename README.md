# Finetuning_llama
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.12+-blue.svg)](https://pytorch.org/)

## Overview
Finetuning_llama is a Python project that fine-tunes the LLaMA-2 7B model for causal language modeling using the Peft library. The project utilizes the Hugging Face Transformers library and the trl library for supervised fine-tuning.

## Key Features
- Fine-tunes the LLaMA-2 7B model for causal language modeling.
- Utilizes the Peft library for LoRA-based fine-tuning.
- Supports 16-bit and 4-bit quantization.
- Integrates with the Hugging Face Transformers library for model loading and tokenization.
- Utilizes the trl library for supervised fine-tuning.
- Saves trained models to the Hugging Face model hub.

## Tech Stack
- **Language**: Python 3.8+
- **Libraries**:
  - `datasets` for loading datasets
  - `peft` for LoRA-based fine-tuning
  - `tensorboard` for logging
  - `torch` for PyTorch
  - `transformers` for Hugging Face Transformers
  - `trl` for supervised fine-tuning
- **Dependencies**: `accelerate`, `bitsandbytes`, `transformers`, `trl`

## Quick Start
### Installation
```bash
pip install -r requirements.txt
```

### Usage
```bash
python fine-tuning-llama-2.py
```
This will fine-tune the LLaMA-2 7B model and save the trained model to the Hugging Face model hub.

## Project Structure
```bash
Finetuning_llama/
|---- fine-tuning-llama-2.py
|---- requirements.txt
|---- README.md
```

## Contributing
Contributions are welcome! Please submit pull requests to the main branch.

## License
Finetuning_llama is released under the MIT License.

MIT License

Copyright (c) [Year] [Author]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.