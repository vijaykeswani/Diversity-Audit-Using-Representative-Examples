### Auditing for Diversity Using Representative Examples

This repository contains code for auditing for diversity of any given data collection using a small set of representative examples.

The goal of providing a label-agnostic algorithm for diversity audit is to enable end-users to audit data collections
even protected attributes (gender, race, dialect, etc.) of the elements in the dataset are unlabeled. 
The algorithm uses a small set of representative examples (called a control set) to provide an approximation of the disparity in the dataset.

To construct control sets, one can either use small randomly chosen labeled samples from the dataset, or use the *adaptive control set* 
procedure provided in the code and paper.

### Examples

We provide examples of our algorithm implementation for two image and one text dataset

- [PPB-2017 dataset](http://gendershades.org/): This is a dataset of portrait images of parliamentarians. The implementation for this dataset is given in the notebook in folder PPB-2017
- [CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html): This is a dataset of images of celebrities. The implementation for this dataset is given in the notebook in folder CelebA
- [TwitterAAE dataset](http://slanglab.cs.umass.edu/TwitterAAE/): This is a dataset of dialect diverse tweets. The implementation for this dataset is given in the notebook in folder TwitterAAE

To run the code, download the datasets from the attached links and place them in appropriate locations mentioned in the notebooks.

### References

*Auditing for Diversity Using Representative Examples* <br>
Vijay Keswani, L. Elisa Celis <br>
ACM-SIGKDD 2021

