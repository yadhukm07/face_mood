# HUMAN DETECTION USING DEEP LEARNING MODEL

Detection of humans from the image captured by the drone images and low altitude drone image using deeplearning model with convolutional nueral network.The final model is developed by trained using 57000 images which is trained on resnet101 which is a faster-rcnn model

Prerequisites:::[Nueral netwoks](http://neuralnetworksanddeeplearning.com/chap1.html),[Convolutional Nueral NEtwork](https://skymind.ai/wiki/convolutional-network)

The project can be devided into 5 phases

1.Data set collection(image collection)

2.Data set preprocessing+Data set annottation/labelling

3.Tf-record Creation

4.installing and deveoloping tensorflow model,installing all the required dependencies and libraries

5.Training and Testing using the dataset on the model

6.Testing with the real examples and retraing by changing various parameters

## PHASE 1:DATA SET COLLECTION

For better accuracy and result the model have to be trained with a well defined dataset. collecting the data set is the first and major work

collected 57000 ariel and drone images

Source
   

  1. [UAV123]--[link](http://neuralnetworksanddeeplearning.com/chap1.html)
   
  2. [Kerala flood images]--[Example link](http://neuralnetworksanddeeplearning.com/chap1.html)

  3. [Flood ariel images]--[sample image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS8eX5lCtfdKNb4OHancP85PjDtlqIHdsz5rUGNsU2SMWi7qJA2)

  4. [Screenshots  from Drone videos of humans from youtube]--[sample video](https://youtu.be/2JuSrDF4bmo)


All collected data::--->[sample video](https://drive.google.com/open?id=1oAzlGOaeC575patIbAZEIPoE3T6NM89)




Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
