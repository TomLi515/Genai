# Text Generation Project

All project code, data processing, model training, and evaluation steps are implemented in a the notebook Text_Project.ipynb. To run the project, simply execute the notebook sequentially from top to bottom. The setup instructions, including data loading, preprocessing, model definitions, and training routines, are included as clearly labeled cells. 

The notebook first prepares the dataset, splits it into training, validation, and test sets, and defines three headline generation models: a Seq2Seq LSTM, a Transformer encoder-decoder, and a fine-tuned GPT-2. For each model, dedicated code blocks handle training, validation, and final testing, with all key hyperparameters defined at the top for easy modification. Evaluation functions compute BLEU and ROUGE metrics for generated headlines, and additional cells provide visualizations for training curves and attention weights. 

For extra credit, I also include a simple interactive GUI, built with ipywidgets, allowing users to input news articles and view generated headlines in real time. All approaches are implemented from scratch except the GPT-2 model, which uses HuggingFace Transformers. No external scripts or files are needed. 

For the three diiferent generation models, the finetuned GPT-2 model achieves the best Test BLEU: 0.0448, ROUGE-1: 0.0771, ROUGE-L: 0.0771.

An example of the interactive GUI can be shown here, where the finetuned GPT-2 model takes the article and genreate a news headline.

<img width="659" alt="18071748367602_ pic" src="https://github.com/user-attachments/assets/02903dc2-faca-4e42-9a32-1b78b83701aa" />



