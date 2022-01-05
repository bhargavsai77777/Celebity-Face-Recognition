The main motive is to make the machine learning models perform their best, In order to do that , below is the pipeline followed.
-->1Data Collection-we need many pictures of the celebrities, and we cannot manually downlaod them. so for that I have used 
                 1) Selinium scrapping
                 2) Fatkun Batch download images
-->2 Data Cleaning: for cleaning the images , I have used haar cascade models in open cv. if in a picture, I am able to see two eyes then , i would use that for training. 
                    mainly used face cascade and eyes cascade
--3) Wavelet Tranforms: used wavelet tranforms to extract the minutte features from thimage, once extracted the wavelet image and raw image are stacked vertically and send this combined image for model training
--4) Model selection, hypter  parameter tuning and training using gradsearchCV 
--5) with the best classifier from above , predict the celebrity in the given picture 



Future scope---use flask server to host on the local machine and deploy it to nay clouds like azure or GCP.
                   
