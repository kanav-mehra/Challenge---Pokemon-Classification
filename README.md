# Challenge - Pokemon Classification

### Multi - Class Image Classficiation Challenge

This challenge is a part of the online Machine Learning course by Coding Blocks. You are going on a trip to Dudhsagar Falls, Goa. To reach the falls you have to cross a huge forest in Collem, so you thought of entering the forest. While you are on your route you spotted multiple Pokemons like Bulbasaur, Pikachu, and Charmander. After coming back, you thought of making a PokeDex - a Pokemon Detector Device which classifies these Pokemons. 
Write an algorithm that classifies these PokeMon's.

### Data Description

There are two folders Test and Train.
#### Train
The train folder consists of a folders named after the Pokemons which contain the images of three types of pokemon and a csv file which maps the images in the folders to the name of that pokemon, The csv contains the field ImageId which is the unique name given to each image and other field is NameOfPokemon which gives the pokemon name associated with that image.

#### Test
Test also contains an image folder on which your model will be tested on and also there is a test csv file which only contains the name or ImageId of the image and gives the order in which each image is to be labelled .
The three categories of Pokemon to be classified are Pikachu, Bulbasaur and Charmander.

#### Solution
The repository highlights 2 approaches to the problem using SVM and Multi-Layer Perceptron algorithms, implemented from scratch. 
Performance - SVM approach achieved 88% accuracy on the Test dataset while the MLP approach achieved around 80% accuracy.
