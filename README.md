# OSIC-Pulmonary-Fibrosis-Progression

This computer vision problem is picked from kaggle. This was a copetition hosted by Open Source Imaging Consortium(OSIC) in collaboration with kaggle. The main aim of this competition was to develop a model which can predict the progression of Pulmunary Fibrosis(PF) with very minute error. More detail about this competition can be found [here](https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression).

Modified version of the Laplace Log Likelihood is used as [Evaluation metrics](https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression/overview/evaluation).

Details about the model used here:
* Two dicom image were given as first two inputs and patient's other metadata was fed as third input. 
* Reidual Blocks are used many times within the CNN network. 
* Check the exact acrhitecture by zooming into this [picture](). 

After submitting on kaggle I got the private score of -6.903 and this is the [notebook](https://www.kaggle.com/purnima29/final-model) used to make the submission. 

:point_right:Check out [my blog](https://purnimachowrasia.medium.com/osic-pulmonary-fibrosis-progression-5f06febebe0) describing approach that I tried in detailed manner. 
