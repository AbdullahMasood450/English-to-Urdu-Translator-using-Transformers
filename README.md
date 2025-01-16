# English-to-Urdu-Translator-using-Transformers

## Research Paper:
[Report](Report.pdf)

## Project Overview 
This project focuses on building a Transformer-based machine translation model to translate English sentences into Urdu using the UMC005: English-Urdu Parallel Corpus. The process includes dataset preprocessing, tokenization (e.g., Byte Pair Encoding), and implementing a Transformer architecture with multi-layer encoders and decoders. The model is fine-tuned with hyperparameter optimization and evaluated using BLEU and ROUGE scores. Additionally, an LSTM model will be implemented for comparative analysis in terms of translation accuracy, loss curve analysis,training time, and inference speed.

## Tools and Technologies Used
Programming Language: Python 

## Libraries 
Keras: For Building the Transformer encoder decoder architecture<br>
matplotlib : For loss and accuracy plots<br>
tokenizers: For word Tokenization and Byte Pair Encoding (BPE)<br>
pandas: For data handling and pre processing<br>
time: For time comparisions of Model<br>

## Techniques Used 
Positional Encoder: To capture the word position of a word in the sentece.<br>
Transformer Encoder : To process the Source Language Embeddings, apply self attention and generate contextual embeddings <br>
Transformer Decoder: To process the target language and perform cross attention with the Souce Language encoder output and generate the target language words in an auto regressive manner. <br>
LSTM: Created redoing the task using LSTM apprach and comapring it with the transformer.<br> 

## Setup and Installination 
1) Clone the repository.<br>
2) Run the first cell to install the libraries.<br>
3) Download the dataset from the repository and change the links in the third cell in the notebook to where the dataset is stored in.<br>
4) Run the rest of the cell to see the results and outputs.<br> 


## Results 

The evaluation results revealed that the Transformer outperformed the LSTM across multiple metrics. It achieved higher accuracy, lower loss, reduced prediction time, and lower perplexity, highlighting its efficiency and effectiveness for English-to-Urdu translation. These improvements underscore the Transformer’s superior capability in handling complex linguistic structures and delivering faster, more accurate translations compared to the LSTM.

![LSTM Validation and Loss](https://github.com/user-attachments/assets/78b6da56-0bb9-41bd-aa4f-edf95911454b)

![Transformer Validation & Loss Plots](https://github.com/user-attachments/assets/521fc60c-b94f-4ce9-ba20-6d3336fca2b3)

![Time and Perflexity Comparision for Transformer and LSTM Models](https://github.com/user-attachments/assets/64dadd5c-9645-43e7-ab94-6b2fa6ceefcb)







