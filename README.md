# Image Classification challenge AN2DL Politecnico di Milano 2022
This is the model that I used in the Image Classification challenge of the course <a href="https://web.archive.org/web/20221129163804/https://codalab.lisn.upsaclay.fr/competitions/8522#learn_the_details-overview">"Artificial Neural Networks and Deep Learning"</a> course held at Politecnico di Milano in 2022.

The challenge consisted on the classification of 8 different plant species from photos with the dimensions (96, 96, 3). The model me and my team developed uses the transfer learning approach with ConvNeXtLarge as the base model. The final model adopted consisted in an ensemble of 3 ConvNeXtLarge models with 8, 16 and 32 batch size respectively. 

Our team reached an accuracy of **93.03**, you can check the results <a href="https://codalab.lisn.upsaclay.fr/competitions/8522#results">here</a>.
