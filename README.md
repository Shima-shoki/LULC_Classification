## LULC_Classification
This is a short tutorial of how to make a Land Use Land Cover (LULC) map by using some machine learning (ML) methods.
Neural Network (NN), Random Forest (RF), Support Vector Machine (SVM) are the famous examples of ML classification, so those methods are going to be used in this example.
You can access the data I used for this tutorial.
The code itself is not well constructed since I'm only a beginner of the python, 
but I hope this work will be helpful for someone wants to implement machine learning methods for the LULC classification with remote sensing data :)

This is the study site (E140.265 to E140.657, N35.805 to N36.003)
![StudySite](https://user-images.githubusercontent.com/47880765/113544941-365d3800-9624-11eb-824d-eb1750da3891.png)

These are the resulting classification maps. We can see there are many solar panels in this region.<br>
Dark orange: Barren land <br> Gray: Built up <br>
Orange: Crop land (mostly rice field) <br>
Red: Solar panel <br>
Green: Vegetation <br>
Blue: Water <br>

NN:![NN](https://user-images.githubusercontent.com/47880765/113545050-6b698a80-9624-11eb-9554-d296d913a874.png)
RF: ![RF](https://user-images.githubusercontent.com/47880765/113545082-77554c80-9624-11eb-8758-f6441bb84932.png)
SVM: ![SVM](https://user-images.githubusercontent.com/47880765/113545096-80deb480-9624-11eb-8aef-336b8a7ebace.png)
