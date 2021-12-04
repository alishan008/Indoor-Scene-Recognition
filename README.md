# Indoor Scene Recognition

Indoor scene recognition is a challenging open problem in high level vision. Most scene recognition models that work well for outdoor scenes perform poorly in the indoor domain. The main difficulty is that while some indoor scenes (e.g. corridors) can be well characterized by global spatial properties, others (e.g., bookstores) are better characterized by the objects they contain. More generally, to address the indoor scenes recognition problem we need a model that can exploit local and global discriminative information.

In order to achieve this, we work with a multi label dataset that provides an exhaustive list of possible indoor setups. The dataset that satisfies this requirement at least to a certain extent can be found on this [link](http://groups.csail.mit.edu/vision/LabelMe/NewImages/indoorCVPR_09.tar) of the MIT website.

![collage2](https://user-images.githubusercontent.com/78029712/144720103-7912b86f-3e2b-4e50-adcb-36ca98985250.png)

This dataset contains images belonging to 67 different classes and each class has a minimum of 100 images. There are various obstacles we face when dealing with such a classification problem. Firstly, the images can closely resemble each other. For example, there are labels such as bakery, bar, deli, fastfood_restaurant and restaurant, and owing to the similarity of the setups of such establishments, it can be challenging to train the neural network. The traditional structure of tables, chairs, platforms, crockery and cultery present in all these labels can cause overlaps. 
