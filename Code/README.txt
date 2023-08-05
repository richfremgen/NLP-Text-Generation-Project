README for NLP Final Project
Group Members: Richard Fremgen, Johnny Antoun, Jaskaran Singh

The contents of this zip file and attachments including the following files:

- nlp_project_paper.pdf: Final project report discussing the training and testing of the Markov and LSTM text generator
- plots_text.pickle: CMU Movie Summary Corpus (500 Summaries) used to train both models in Section 4 of the paper
- det_syn_data.pkl: Deterministic synthetic data generation that was used in Section 5
- non_det_syn_data.pkl: Stochastic synthetic data generation that was used in Section 5
- gen_prob_model.ipynb: Python code used to generate Markov model, along with the output of Section 4 and 5 training/testing.
- Final_Project_2.ipynb: Neural Network that was trained on real data (input, target length of two)
- Final_Project_5.ipynb: Neural Network that was trained on real data (input, target length of five)
- synthetic_deterministic.ipynb: Neural Network that was trained on synthetic data generated through a deterministic process. (input, target length of two)
- synthetic_nondeterministic.ipynb: Neural Network that was trained on synthetic data generated through a non-deterministic process. (input, target length of two)
- model_2.pt: Weights for Neural Network trained on real data (input, target length of two)
- model_5.pt: Weights for Neural Network trained on real data (input, target length of five)
- model_det_synth.pt: Weights for Neural Network trained on synthetic data generated through a deterministic process. (input, target length of two)
- model_nondet_synth.pt: Weights for Neural Network trained on synthetic data generated through a non-deterministic process. (input, target length of two)

The following References were used:

References

- Build a Natural Language Generation (NLG) System using PyTorch - Code for LSTM Model (Section 3, 4, 5) https://www.analyticsvidhya.com/blog/2020/08/build-a-natural-language-generation-nlg-system-using-pytorch/ 
- Text Generation using PyTorch LSTM Networks* https://coderzcolumn.com/tutorials/artificial-intelligence/text-generation-using-pytorch-lstm-networks-and-character-embeddings 
- CMU Movie Summary Corpus* - http://www.cs.cmu.edu/~ark/personas/ 
- Learning Latent Personas of Film Characters - David Bamman, Brendan O'Connor, Noah A. Smith
- Speech and Language Processing - Daniel Jurafsky & James H. Martin
