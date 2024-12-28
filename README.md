Exploring The Sound of Seattle Birds with Neural Networks

Abstract:

In this report, neural networks are employed to identify the bird species of Seattle. We used spectrograms that were derived from Xeno-Canto’s Birdcall competition dataset that consists of 10 high-quality MP3 sound clips for each of the 12 selected bird species[1]. Additionally, three MP3 bird call recordings were available for external testing. The primary goal is to classify bird species based on their distinct vocalizations. We developed two custom neural network models: a binary classification model distinguishing between the American Crow and the Blue Jay, and a multi-class classification model capable of identifying any of the 12 bird species. Predictions on the three external test clips are made to assess the effectiveness of the models. Neural Networks with different architectures and parameters were employed to find the most efficient model.. For hidden layers, various activation functions such as Relu, SoftMax, or Leaky Relu were used. The report concludes with a discussion on alternative modeling approaches and the suitability of neural networks for this specific application.

Introduction:

In this study, a neural network is employed to categorize bird species using pre-processed spectrograms of their sounds. The dataset, originating from Xeno-Canto’s Birdcall competition,  comprises original sound clips recorded in the Seattle area. Each clip has been preprocessed into spectrograms, which act as visual representations of the bird sounds and serve as the primary input to the neural networks. These spectrograms are organized in HDF5 format. 

The main objective is to develop a robust neural network which can accurately predict species based on their unique sound patterns. We have performed binary as well as multi-class classification tasks on the dataset. We developed various neural network models for the binary classification task to distinguish between the American Crow and the Blue Jay. We used a convolutional neural network for the multi-class classification task that is capable of identifying any of the 12 bird species namely American crow, Barn swallow, Black-capped chickadee, Blue jay, Dark-eyed junco, House-finch, Mallard, Northern flicker, Red-winged blackbird, Stellar’s jay, Western meadowlark, White-crowned sparrow. We have also done a comparative analysis of diverse network structures and hyperparameters to identify the most suitable and efficient model for these kind of classification tasks.

The limitations are discussed in detail for each classification task. Automatic species classification of birds from their sounds has many potential applications in conservation, ecology and archival [2]. The findings of this study can not only help in understanding their unique behavior but also serve as a tool for monitoring bird population and maintaining diversity. 
