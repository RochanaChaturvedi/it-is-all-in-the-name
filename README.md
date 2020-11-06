# It's All in the Name

This repository provides the replication code in python 3.0 for the paper [It's All in the Name:  A Character Based Approach To Infer Religion](https://arxiv.org/abs/2010.14479) where we predict religion from personal names only. We train character based classifiers: logistic regression, support vector machine as well as convolutional neural network. The models can predict religion, i.e., Buddhist, Christian, Hindu, Jain, Muslim and Sikh with over 97% accuracy and provide 100% coverage.

## Datasets and Models
The models are trained using Rural Economic and Demographic Survey collected by the National Council of Applied Economic Research. This data set is proprietary. Therefore, we annotate the religion of 20,000 randomly selected household heads from rural Uttar Pradesh largely comprising Hindus and Muslims. This dataset can be used to test for improvements in subsequent works (available on request for academic purposes only). 

As a cautionary measure, we are not sharing our models with this repository. If you are an academic researcher, please feel free to shoot us an email and we will be happy to provide you the trained models and answer any questions.

## How to improve Predictions
The models can make predictions using single person's name, however the accuracy improves when we combine a person's name with the name of a relative such as parent/spouse.

## Licence and citation
The code is licenced under AGPL-3.0 licence (see LICENCE).

If you find the work useful please cite it as: <br/>
Chaturvedi, Rochana, & Chaturvedi, Sugat. 2020. It’s All in the Name: A Character BasedApproach To Infer Religion. arXiv preprint arXiv:2010.14479. <br/>

BibTeX: <br/>
@article{chaturvedi2020s, <br/>
  title={It's All in the Name: A Character Based Approach To Infer Religion}, <br/>
  author={Chaturvedi, Rochana and Chaturvedi, Sugat}, <br/>
  journal={arXiv preprint arXiv:2010.14479}, <br/>
  year={2020} <br/>
}

## Contact:

* [Rochana Chaturvedi](https://twitter.com/rochanac?lang=en): rochana [dot] chaturvedi [at] gmail [dot] com
* [Sugat Chaturvedi](https://sites.google.com/view/sugatchaturvedi/home): sugat [dot] chaturvedi [at] gmail [dot] com
