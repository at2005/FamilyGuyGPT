# FamilyGuyGPT
Generative Language Model for Family Guy Scripts

A GPT-like transformer language model for generating Family Guy scripts, inspired by @karpathy's GPT-from-scratch video. Mainly a personal "learning experience" project.

Some modifications however:
- I use batch multi-head attention
- Byte-pair encoding instead of character-level. This allows model to spend less time learning commonly-recurring words such as "Peter" and "Lois"
- Context window increased to 380, embedding dimension also increased to 480
- KV Cache for fast inference timing

Run code in scraper.ipynb first to generate .txt file of Family Guy scripts. Then run gpt.ipynb which contains GPT model code.

Email me for weights at SurnamePronom at gmail dot com. 
