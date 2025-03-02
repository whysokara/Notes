Lecture : (https://www.youtube.com/watch?v=7xTGNNLPyMI)
## Title : Deep Dive into LLMs like ChatGPT

### Important Links used in the lecture:
https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1
tokenizer : https://tiktokenizer.vercel.app

Steps to create a tool something like ChatGPT:
1. Pretraining
Pretraining is basically downloading all the data from internet.
then they filter those internet data in number of steps like
- URL filtering (Blocking spam malicious racist blog urls)
- Language fitering (for ex: scrapping data only whereenglish is >65%)
and many more conditions

2. Tokenization
== Conversion of english text to bits and bytes
text => bits => bytes


"" task is to reduce the space and text space of raw text "" also known as tokenization
Basically you give a symbol to a text and then in next step you look for pairs of symbol that comes together and then give them a new symbol and you keep on doing this on and on

3. Neural Network training
