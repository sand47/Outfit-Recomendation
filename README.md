# Outfit-Recomendation

Dress recommendation to users is a challenging task as various kinds of color combination are possible.We have consider men clothing of various color combination which includes colors such as black,white,yellow,blue,organge,gray and various other color. I collected data from google images and manually cleaned images to form a training set of 550 and test of 75 <br>

In this project I have extracted features using pretrained VGG16 and recommend k dress(k can be varied) using KNN.<br>

# Training and inference 
To train the code <br><br>
python similar_images_TL.py 
<br>
## Inference 

In the similar_images_TL.py you can change the test folder name and a output folder is automatically created and recommend images are saved. 

![alt text](https://github.com/sand47/Outfit-Recomendation/blob/master/output/rec/informalred84_rec.png)
