# Learning Resources

This list is for workshop attendees who want to keep learning after the Openchp Talent Arena hands-on session.

If you're new, follow the sections in order:
1. PyTorch basics
2. Transformer fundamentals
3. Tokenization
4. Practice projects

## 1. PyTorch Basics

- PyTorch Tutorials (official hub): https://docs.pytorch.org/tutorials/
  - Best starting point for all official beginner material.
- Learn the Basics (official): https://docs.pytorch.org/tutorials/beginner/basics/intro.html
  - Gentle walkthrough of tensors, models, optimization, and saving models.
- Quickstart: https://docs.pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html
  - Fast end-to-end training example.
- Build the Neural Network: https://docs.pytorch.org/tutorials/beginner/basics/buildmodel_tutorial.html
  - Understand `nn.Module` and model structure.
- Automatic Differentiation (`autograd`): https://docs.pytorch.org/tutorials/beginner/basics/autogradqs_tutorial.html
  - Core backprop concept in practical PyTorch form.
- What is `torch.nn` really?: https://docs.pytorch.org/tutorials/beginner/nn_tutorial.html
  - Great for understanding how PyTorch training loops work under the hood.

## 2. Transformers Fundamentals

- Transformer Explainer: https://poloclub.github.io/transformer-explainer/
  - One of the easiest visual explanations of attention and Transformer blocks.
- Attention Is All You Need (original paper): https://arxiv.org/abs/1706.03762
  - Foundational paper that introduced Transformers.
- Hugging Face LLM Course (Chapter 1): https://huggingface.co/learn/llm-course/chapter1/1
  - Beginner-friendly practical course for modern Transformer workflows.

## 3. Tokenization (Important for GPT Models)

- OpenAI `tiktoken` repository: https://github.com/openai/tiktoken
  - Fast BPE tokenizer used with OpenAI models; useful to understand token IDs and context windows.
- Hugging Face Tokenizers Quicktour: https://huggingface.co/docs/tokenizers/quicktour
  - Good intro to how tokenizers are trained and applied.


## Workshop-Specific Practice

- Main notebook in this repo: `build_gpt.ipynb`
- Setup script in this repo: `./init.sh`
