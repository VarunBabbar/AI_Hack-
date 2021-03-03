# Imperial AI_Hack 
In this hackathon we predict crop yields using a combination of EVI and temperature data. The jupyter notebooks show the pre-processing steps as well as the predictive models used.
1) The initial model used was a CNN which acted on concatenated EVI and temperature data aggregated across different locations in Illinois. The architecture was a modified version of the one found at https://github.com/gabrieltseng/pycrop-yield-prediction. 
2) A Gaussian Process model was then applied to the final layer features of the CNN as well as additional latitude and longitude data. 
3) Yield predictions from both models were compared and the final output was the ensemble average of the two models. 
4) We get around 11% average error on our validation set.


To run the notebooks:
1. Install jupyter notebooks on your local machine
2. Clone this repository
3. Open the .ipynb file by running a jupyter notebook server on your machine 
