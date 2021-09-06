# CNN-Dog_vs_Cat

it is a python pytorch CNN model to identify wether the animal is DOG or CAT

Download data set from this link : https://www.microsoft.com/en-us/download/details.aspx?id=54765
you got file structur like this 
    -kagglecatsanddogs_3367a
        -PetImages
            -DOG
                -dog_img.jpeg
                -...
            -CAT
                -cat_img.jpeg
                -...

your data set is stored in a tensor format with this name : "Data_set.npy" 

your cnn_model is storeed in compresed zip format with this name : "Dog_Cat_trained_model.pth"

identify dog or cat 
if your predicted output is 0 it means your predicted outcome is "cat" 
if your predicted output is 1 it means your predicted outcome is "dog" 
{CATS: 0, DOGS: 1}


