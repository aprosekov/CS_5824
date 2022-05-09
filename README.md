The code.ipynb file has all the code that we used to create a test out model.<br>
<br>  
The expected file structure is <br>
folder: <br>
-------code.ipynb <br>
-------GSVImages: (image folder)<br>
----------------* .png <br>
-------Panoid_heat_label.csv (csv of panoid and heat labels) <br>

<br>
<br>

The packages that are used are tensorflow, pandas, and matplotlib.<br>
<br>
Just running all the code chunks will use our saved model and predict the testing data using our saved model.<br>
<br>
There are 4 code chunks that are commented out, the 1st being a function that makes sure all of images are not corrupted, the 2nd and 3rd being model that we tried, with the max pooling model being our final model and the last commented code chunk is us training the model. 

