# English proficiency prediction NLP

<b>Description : </b>

IAS module project at ENIB (SP9 - 2021)

Basically the idea of the project is to predict the someone's English proficiency based on a text input. 

We used the The NICT JLE Corpus available here : https://alaginrc.nict.go.jp/nict_jle/index_E.html

The source of the corpus data is the transcripts of the audio-recorded speech samples of 1,281 participants (1.2 million words, 300 hours in total) of English oral proficiency interview test. Each participant got a SST (Standard Speaking Test) score between 1 (low proficiency) and 9 (high proficiency) based on this test. 


<b>Tasks : </b>

- Pre-process the dataset: extract the participant transcript (all `<B><B/>` tags). Inside participant transcript, you can remove all other tags and extract only English words.
- Process the dataset: extract features with the Bag of Word (BoW) technique
- Train a classifier to predict the SST score
- Compute the accuracy of your system (the number of participant classified correctly) and plot the confusion matrix.
- Try to improve your system (for example you can try to use GloVe instead of BoW). 

<b>Supervisor :</b>

Olivier Augereau

<b>Authors :</b> 

CORREA, Elias

GASSIBE, Franco
