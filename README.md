## Dataset

Download <code>SBP22_Meta_Ad_Covid_dataset.csv</code>

## Description
We divide the categories into eight different themes: Prevention, Treatment, Di-
agnosis, Mechanism, Case Report, Transmission, Forecasting, and General.

We have asked two members of our team to label each sample in a multi-class fashion, which means one sample can be assigned to more or equal to one category.

The instructions for the labeling process requires reading only the text content
of the ad, and checking every applicable options in the suggested categories.

For example, if an ad talks about vaccination and the rising number of cases,
the category of both categories ‘Treatment’ and ‘Case Report’ will be filled with 1
and others will be filled with 0. As shown in statistics of categories in Table 1,
there is imbalance between the number of classes. This is because most of the ads include
content related to ‘General’ as advertisers frequently talk or quote about personal stories
to let audience engaged in the message.

We publicly release the data by providing the list of IDs of Meta ads and the corresponding
annotation in our github according to the [terms of service of Meta](https://developers.facebook.com/terms/)

## Citation
If you are using this repo, please cite our work:
```bash
@inproceedings{jeong2022classifying,
  title={Classifying COVID-19 Related Meta Ads Using Discourse Representation Through a Hypergraph},
  author={Jeong, Ujun and Alghamdi, Zeyad and Ding, Kaize and Cheng, Lu and Li, Baoxin and Liu, Huan},
  booktitle={International Conference on Social Computing, Behavioral-Cultural Modeling and Prediction and Behavior Representation in Modeling and Simulation},
  pages={35--45},
  year={2022},
  organization={Springer}
}
```
