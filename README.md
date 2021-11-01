# deep-learning
Detection Stage of Leukemia Cancer (G1, G2 and S) using CNN and VGG19

This was a project that was done within the time frame of 24 hours for a Hackathon contest. 

What inspired us for the Hackathon
We decided to start with the dataset that was shared by Iing's PostDoc friend (who permitted us to share this knowledge in this Hackathon) since we desire to help patients that are facing Leukemia. We wish to help the patients with Leukemia so they can detect the stage of their cancer earlier and thus receive the treatment they deserve.

What this project does
We have in total 1195 images of cancer cells that we desire to scan accurately. The greater the number of images that needed to be scanned, the less likely the accuracy of the pictures is to be.

Libraries from Python that are being used:
  - Keras (Main library): It wraps the efficient numerical computation libraries Theano and TensorFlow by offering consistent and simple APIs 
  - Matplotlib: Library for creating interactive, static, and animated visualizations
   The deep learning architecture that was used is Convolutional Neural Network and VGG16. The concept consists of each neuron receiving several inputs. We take a weighted sum over them, pass it through an activation function and respond with an output.
   
   How we built it
Our project is a new output that was edited from the code of https://www.kaggle.com/fanconic/cnn-for-skin-cancer-detection. The database, which consists of cancer cells retrieved from patients that are facing Leukemia, was permitted by Iing Muttakhiroh’s senior to share. To open the images to get clearer images, we used link.

The code is split into 3 main segments: processing image, split data, and training the data. We share the dataset through Google Drive. We were trying to do Image Augmentation but we have not finished yet.

70% of our code namely consists of splitting the data, 15% for training tests, and 15% for validation.


