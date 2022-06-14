# backprop_nns_mnist

As a project for artificial intelligence course I took up the challenge to implement everything it takes to train a dense neural network (nn henceforth) with backpropagation using only numpy library. Then I trained the nn to distinguish the MNIST database digits.

During this project I learned that it's a terrible idea to train the nn using all of your training data at once. It takes A LOT longer and the accuracy of the model is significantly worse. May this be a lesson for those coming after me.

For reference 2 identical nns with 2 hidden layers trained with 60k (all the training data I had) and 100 data units produced these results:

batch size of 60k:
![image](https://user-images.githubusercontent.com/59236770/173581226-24f75968-75f5-49ec-917d-7c70ac95d46b.png)

batch size of a 100:
![image](https://user-images.githubusercontent.com/59236770/173581367-f25a4eb1-c202-4e7a-b0ab-ab376a3c8221.png)

Feel free to use this for anything.
