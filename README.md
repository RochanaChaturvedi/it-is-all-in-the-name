Note: This repository is now deprecated and the updated code is made available at following Harvard Dataverse link: https://doi.org/10.7910/DVN/JOEVPN

If you find the work useful, please cite our paper and the dataverse entry as follows:
BibTeX: <br/>
@article{chaturvedi2020s, <br/>
@article{chaturvedi_chaturvedi_2023, <br/>
title={It’s All in the Name: A Character-Based Approach to Infer Religion}, <br/>
DOI={10.1017/pan.2023.6}, <br/>
journal={Political Analysis}, <br/>
publisher={Cambridge University Press},<br/>
author={Chaturvedi, Rochana and Chaturvedi, Sugat}, <br/>
year={2023},<br/>
pages={1–16}<br/>
}

@data{DVN/JOEVPN_2023,<br/>
author = {Chaturvedi, Rochana and Chaturvedi, Sugat},<br/>
publisher = {Harvard Dataverse},<br/>
title = {{Replication Data for: It’s All in the Name: A Character Based Approach to Infer Religion}},<br/>
year = {2023},<br/>
version = {V1},<br/>
doi = {10.7910/DVN/JOEVPN},<br/>
url = {https://doi.org/10.7910/DVN/JOEVPN}<br/>
}

# It's All in the Name
This repository provides the Python 3.0 replication code for the paper [It's All in the Name:  A Character Based Approach To Infer Religion](https://arxiv.org/abs/2010.14479) where we predict religion from personal names only. We train character based classifiers: logistic regression, support vector machine as well as convolutional neural network. The models can predict religion, i.e., Buddhist, Christian, Hindu, Jain, Muslim and Sikh with over 97% accuracy and provide 100% coverage.

## Datasets and Models
The models are trained using Rural Economic and Demographic Survey collected by the National Council of Applied Economic Research. instructions for obtaining this dataset are available at http://adfdell.pstc.brown.edu/arisreds_data/readme.txt. We also annotate the religion of 20,000 randomly selected household heads from rural Uttar Pradesh largely comprising Hindus and Muslims. This dataset can be used to test for improvements in subsequent works.

If you are an academic researcher, please feel free to shoot us an email and we will be happy to answer any questions.

## How to improve Predictions
The models can make predictions using single person's name, however the accuracy improves when we combine a person's name with the name of a relative such as parent/spouse.

## License and citation
The code is licenced under GNU Affero General Public License version 3 (AGPL-3.0, see LICENCE).


## Contact:

* [Rochana Chaturvedi](https://twitter.com/rochanac?lang=en): rochana [dot] chaturvedi [at] gmail [dot] com
* [Sugat Chaturvedi](https://sites.google.com/view/sugatchaturvedi/home): sugat [dot] chaturvedi [at] gmail [dot] com
