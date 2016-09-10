# ImageCollectionSystem

NOTE: very early stages of development, will be subject to change.

Abstract

The goal of this project is to create a system which can collect and classify images accurately by names and subcategorys and deposite them into a virtual repositry for the purpose of future machine learning applications. Using classic image search engines like Google Images, the system must be able to search for images by keyword then distinguish images which are accurate to the keyword from images which are not. The system will follow the model proposed by Kaiji Yanai [1] which splits the process into 2 stages, Collection and Selection, and will attempt to maintain as high of an accuracy as possible in hope that the resulting respository may be useful for Neural Network studies. In the hope of maintaining high accuracy the system will use methods such as signature quadratic form distance calculation [2] in order to attribute numerical values to the similarity of images, and will employ other yet to be determined methods by which to distinguish accuracy. 
