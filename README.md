# ChatBot using Seq2Seq model

In this project I made a chatbot that uses Seq2Seq model with attention with Tensorflow.

## Getting Started

### Prerequisites
Running this project on your local system requires the following packages to be installed :

* Tensorflow
* jsonpickle
* numpy
* pandas
* os


They can be installed from the Python Package Index using pip as follows :
 
     pip install numpy
     pip install jsonpickle
     pip install pandas
     pip install tensorflow
     pip install tensorflow-gpu
     
     
## Training a model
To train a model from a python console:

1. Configure the [hparams.json](seq2seq-chatbot/hparams.json) file to the desired training hyperparameters

2. Set console working directory to the **seq2seq-chatbot** directory. This directory should have the **models** and **datasets** directories directly within it.

3. To train a new model, run train.py with the dataset path:
```shell
run train.py --datasetdir=datasets\dataset_name
```
 
### To chat with a trained model from a python console:

1. Set console working directory to the **seq2seq-chatbot** directory. This directory should have the **models** and **datasets** directories directly within it.

2. Run chat.py with the model checkpoint path:
```shell
run chat.py models\dataset_name\model_name\checkpoint.ckpt
```

The result should look like this:

![chat](doc_files/chat.png "chat")



## Tools Used



## Contributing
You are welcome to contribute :

1. Fork it (https://github.com/ritwik-singh/chatbot/fork)
2. Create new branch : `git checkout -b new_feature`
3. Commit your changes : `git commit -am 'Added new_feature'`
4. Push to the branch : `git push origin new_feature`
5. Submit a pull request !
If you have any new ideas or suggestions to improve this project, feel free to contact me. Your valuable feedback is highly appreciated!

## License
This Project is licensed under the MIT License, see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This implementation was inspired by:
- Kirill Eremenko & Hadelin de Ponteves [Deep NLP Udemy course](https://www.udemy.com/chatbot/)
- TensorFlow's [Neural Machine Translation (seq2seq) Tutorial](https://www.tensorflow.org/tutorials/seq2seq)
- [TF NMT GitHub](https://github.com/tensorflow/nmt)
- (https://github.com/AbrahamSanders/seq2seq-chatbot/blob/master/README.md)


## Final Notes
**Thanks for going through this Repository! Have a nice day.**</br>
</br>**Got any Queries? Feel free to contact me.**</br>
</br>**Ritwik Kumar Singh**
<p align="left">
<a href="mailto:ritwiksingh39@gmail.com"><img src="https://github.com/rohanrao619/Icons/blob/master/SVGs/Gmail.svg" height ="45" title="Gmail" alt="mailto:ritwiksingh39@gmail.com"></a>
<a href="https://github.com/ritwik-singh"><img src="https://github.com/rohanrao619/Icons/blob/master/SVGs/GitHub.svg" height ="45" title="GitHub" alt="https://github.com/ritwik-singh"></a>
<a href="https://www.linkedin.com/in/ritwiksingh28"><img src="https://github.com/rohanrao619/Icons/blob/master/SVGs/LinkedIn.svg" height ="45" title="LinkedIn" alt="https://www.linkedin.com/in/ritwiksingh28"></a>
</p>
