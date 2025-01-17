

# Agriprotec

## Abstract
Time since there existed the problem of wild animals entering and destroying crops in farmlands adjoining forests in Kerala.As per the field survey conducted by  Kerala Forest
Department, the main animals involved in crop damage were elephant (Elephas maximus ),gaur (Bos gaurus), sambar (Cervus unicolor), wild boar (Sus scrofa ), bonnet macaque (Macaca radiata), common langur (Presbytis entellus).Among these,elephant and wild boar did maximum damage.Conventional system of electrified wire fences is not an efficient method as long-term success has often fallen well below expectation and also due to the danger to non-targeted species.

As per the research conduched by Lucy King, a graduate student from the University of Oxford confirmed the existance of elephantine phobia towars sounds of angry buzzing bees.


As a solution to this problem,Agriprotec has made a system that tracks,identifies and takes apt defence against the targeted threat only.In this method we implant PIR sensors +camera combo running completely on solar power.When it detects motion of any animal, it tiggers the microcontroller and activates it  from sleep mode and activates the  camera system which captures images from the currently active sensor area and forwards it to a master system nearby.It then  processes the image and identifies if it is an elephant or boar or any other animals,humans.If it is an elephant then the system activates the siren which produces buzzing sound and if it's a wild boar then system activates the strobe light + drumming sound combo.By this kind of system we are able to save cost and electric energy compared to electrified fences.

## Research Question 
There has been a constant rise in the number of attacks by wild animals on lands near forest or such other areas. Primarily agricultural land, which happens to be free food for the invaders.Is there a solution to eradicate this situation?

## Dataset
An annotated camera-trap dataset of 20 species commonly found in North - America is used for training the model. The dataset contains 15826 images of 20 species namely Agouti, Bird spec, Coiban Agouti, Collared Peccary, Common Opossum, European
Hare, Great Tinamou, Mouflon, Ocelot, Paca, Red Brocket Deer, Red Deer, Red Fox, Red Squirrel, Roe Deer, Spiny Rat, White Tailed Deer, White-nosed Coati, Wild Boar, and Wood Mouse. The dataset contains a collection of gray-scale and color images. 

The images captured at night are in gray-scales and images captured in daytime are in colored.

Every image contains only one species out of 20 species. 80% of the dataset, i.e., 12660 images is used for training and the rest 20% for testing.

Link to Dataset Repo 

https://data.world/deana/camera-traped-wild-animals-images

or

https://drive.google.com/open?id=14vII7LJP8Hv-Uz4Av5DA33_Hyz95PL0I


![](Images/Page_00.png)
![](Images/Page_01.png)

## 

## Hardware Used

PIR Sensors,ESP32 CAM,MASTER SYSTEM,AUDIO SPEAKERS

# Establishment of Agriprotec System
The Agriprotec sensors can be placed near the borders of the farmland attached onto a pole of 3m height and are used to detect the presence of animals, mainly elephants and wild boars.Each sensor placed at a distance of 20m apart.Then the Master system is placed near center of farmarea.


# Programming language used
Python 3 is used as the programming language with keras framework using tensorflow backend image recognition 

# Results 




# Conclusions



