# Learning-to-rank from implicit feedback

## Introduction
This is a hub of our research on learning-to-rank from implicit feedback for recommender systems. As a case study, we chose to do experiments on the real-world service named Sobazaar. The more details on Sobazaar is given as follows.

## Dataset description
Sobazaar is a social fashion app developed by Telenor Digital. The app lets you view many different pieces of fashion clothing and it is possible for users to design their own boards. A board is a collection of items that the users have selected,  see Figure (a).
![myimage-alt-tag](https://github.com/hainguyen-telenor/Learning-to-rank-from-implicit-feedback/blob/master/image/Sobazaar.png)

Notice also from Figure (a) that there is a heart in the lower left corner. It is possible for users to love items and boards. A user have a lovelist where all the items and boards that the users have loved are displayed. The love button of Sobazaar can be compared to the ”like button” of Facebook. Each user have a news feed that will display items that the app believes the user is interested in. The feed will also include news about what followed users are doing and what items that they have loved. The love list is a nice way for the app to keep track of what items a user may be interested in. These items can then be used to create an interesting feed for the users and hence create value for the user.

Sobazaar has the capability to let users buy items, but not directly. The app is a storefront for many different fashion stores and clicking the purchase button does not let you purchase the item in the Sobazaar app, but will instead take you to the homepage of the specific store that you are browsing and from there the item can be bought. See Figure (b) for an example of what the purchase option may look like. With regard to images we can see from Figure (b) that there is not much information about the item displayed. The displayed information is the product title, the price, and the product image.

What separates Sobazaar from any ordinary web-shop is the social part. Sobazaar lets users follow and unfollow each other. Sobazaar uses directional links between users, that is, a user a can follow a user b without user b having to follow user a. Figure (c) shows the app display when selecting to follow or not follow a user. Below the user we can choose to follow, is a selection of images of the items that the user have interacted with. These images will give us a taste of the fashion sense of the user before we choose to follow or not. The use of images as an indicator for whether a user should be followed or not further reinforces our theory that images are important for choosing who to follow.

## Dataset usage license
The dataset can be used only for research purposes and the usage must be followed the Open Database License (ODbL) v1.0: http://opendatacommons.org/licenses/odbl/1.0/

## Downloads
The dataset can be downloaded in the folder named [/data](https://github.com/hainguyen-telenor/Fashion-Recommender-Systems/tree/master/Data). There is a README.md file, which provides the meanings of different columns in the dataset.

## Research papers
[1] Hai Thanh Nguyen, Thomas Almenningen, Martin Havig, Herman Schistad, Anders Kofod-Petersen, Helge Langseth, and Heri Ramampiaro. Learning to rank for personalised fashion recommender systems via implicit feed- back. In Mining Intelligence and Knowledge Exploration - Second International Conference, MIKE 2014, Cork, Ireland, December 10-12, 2014. Proceedings, pages 51–61, 2014.[Link](http://dx.doi.org/10.1007/978-3-319-13817-6_6)

[2] Huihuai Qiu, Jie Zhang, Guibing Guo, Hai Thanh Nguyen, Zhu Sun, and Yun Liu. “TBPR: Trinity Preference based Bayesian Personalized Ranking for Multivariate Implicit Feedback”. [24th Conference on User Modeling, Adaptation and Personalization](http://www.um.org/umap2016/) (Accepted for publication)

[3] Heri Ramampiaro, Helge Langseth, Thomas Almenningen, Herman Schistad, Martin Havig, and Hai Thanh Nguyen. New Ideas in ranking for Personalised Fashion Recommender Systems. Chapter in the book: "Business and Consumer Analytics: New Directions” (Vol 1), Springer. (Accepted for publication)
