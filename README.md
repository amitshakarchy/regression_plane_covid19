# regression_plane_covid19

In this project, I perform cellular image-based analysis in supervised manner with no domain knowledge required using the Regression Plane (RP) concept, to identify potential treatments for COVID-19 and analyze the effect of treatment’s dosage on the treated cells. RP is a methodology for modelling and analyzing biological processes using 2-dimensional (2D) regression. (Regression plane concept for analysing continuous cellular processes with machine learning
https://www.nature.com/articles/s41467-021-22866-x).

The study focuses on evaluating and applying the RP-based approach on the “RxRx19a” dataset (https://www.rxrx.ai/rxrx19a). The drug screening dataset, which aims to enable the evaluation of the effectiveness of treatments on active SARS-CoV-2 infection in human cells, consists of screening images and their corresponding deep learning embeddings. 1,670 compounds were tested in various dosages on two different cell types - normal human renal cortical epithelial cells (HRCE) and african green monkey kidney epithelial cells (Vero). Additionally, for the sake of comparison between the treated active cells to “healthy” cells, inactive SARS-CoV-2 ultraviolet-irradiated (UV-IR) and mock cells were included. Over 300,000 Immunofluorescence screening images (1024x1024) of the wells were taken in five channels, one for each unique stain. In addition, the authors provided embeddings (1024) of these images that were extracted using deep learning neural network trained for the identification of distinct phenotypic profiles. 


07/2022
