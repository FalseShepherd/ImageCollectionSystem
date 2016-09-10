# ImageCollectionSystem

NOTE: very early stages of development, will be subject to change.

Abstract

The goal of this project is to create a system which can collect and classify images accurately by names and subcategorys and deposite them into a virtual repositry for the purpose of future machine learning applications. Using classic image search engines like Google Images, the system must be able to search for images by keyword then distinguish images which are accurate to the keyword from images which are not. The system will follow the model proposed by Kaiji Yanai [1] which splits the process into 2 stages, Collection and Selection, and will attempt to maintain as high of an accuracy as possible in hope that the resulting respository may be useful for Neural Network studies. In the hope of maintaining high accuracy the system will use methods such as signature quadratic form distance calculation [2] in order to attribute numerical values to the similarity of images, and will employ other yet to be determined methods by which to distinguish accuracy. 

[1]. http://delivery.acm.org/10.1145/1250000/1242816/p1295-yanai.pdf?ip=147.142.150.250&id=1242816&acc=ACTIVE%20SERVICE&key=2BA2C432AB83DA15%2E4992EA3396EC4E12%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&CFID=836224975&CFTOKEN=40017478&__acm__=1473500695_05c81be037971b38cdbece53dc126108 , Keiji Yanai, The University of Electro-Communications, 2007.

[2]. dme.rwth-aachen.de/en/system/files/file_upload/publications/p697-beecks.pdf, Christian Beeks et al. , Data Management and Data
Exploration Group RWTH Aachen University, 2009.
