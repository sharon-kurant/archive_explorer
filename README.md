# The interlinearity toolbox
This toolbox was developed in the framework of the ERC project [Textual Microcosms: A New Approach in Translation Studies](https://textualmicrocosms.huji.ac.il/), led by prof. Ronit Ricci at the Hebrew University of Jerusalem. The project strives to explore and document the phenomenon of interlinear translations produced between the late 16th and 20th centuries in the Indonesian-Malay world. This computer vision toolbox was devised to facilitate the mission of retrieving pages that contain interlinear translations among a vast number of manuscripts digitized in collections throughout the world, such as the British library’s Endangered Archives Project, Qalamos, Dreamsea, Leiden University manuscript collections and others. 

You will find here:
* A collab notebook that …. on an image collection and uses t-SNE (t-distributed Stochastic Neighbor Embedding) to reduce dimensions and visualize the pages as dots on a two dimensional figure. The notebook enables inclusion of tagged sets that will be colored in the figure, and lets the user explore the clusters, interpret and mine it by selecting areas in the figure and downloading them. 



![WhatsApp Image 2024-04-24 at 17 03 08_fe01861b](https://github.com/sharon-kurant/interlinearity_toolbox/assets/65344674/49ec196e-44be-4e92-aaa7-28f385896191)
(interpreting the clusters in our t-SNE we found different types of objects in the collections. The clusters that included orange colored dots are those that included images pre-annotated as including interlinear translations.
* A collab notebook that enables training a custom model to recognize a visual phenomenon in a collection of images (in our case, interlinear lines).  The model can then be used to classify a collection according to a chosen threshold of confidence and output a csv of the results. 
To download the model we trained for interlinearity detection, click  [here](https://drive.google.com/drive/folders/10mdS8AKVqfd7svAZCgSEIkrbuer3gmX1?usp=sharing). 


