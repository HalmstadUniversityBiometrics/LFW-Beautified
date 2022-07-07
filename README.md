# LFW-Beautified
**LFW-Beautified: A Dataset of Face Images with Beautification and Augmented Reality Filters**

Selfie images enjoy huge popularity and acceptability in social media platforms. The same platforms centered around sharing this type of images offer different filters to “beautify” them or to incorporate augmented reality effects (like noses or glasses) before they are uploaded. Studies suggests that filtered images are likely to attract more views, comments, and engagement of others. Selfie images are also in increasing use in security applications due to mobiles becoming data hubs for many transactions. Also, video conference applications, which have boomed during the pandemic, include beautification or augmented reality filters. 

Such filters may destroy or modify biometric features that would allow person recognition or even detection of the face itself, even if such commodity applications are not necessarily used with the purpose of compromising facial systems. This could compromise the normal operation of such systems, or subsequent investigations like crimes in social media, where automatic analysis is usually necessary given the amount of information posted in social sites or stored in devices or cloud repositories. 

To help in counteracting the mentioned issues and allow fundamental studies with a common public benchmark, we contribute with a database of facial images that includes the application of several image manipulations like those found in social media. The database includes image enhancement filters (which mostly modify contrast and lightning) as well as augmented reality filters that incorporate items like “Dog nose”, “Transparent glasses”, “Sunglasses with slight transparency”, and “Sunglasses with no transparency” to the face image. Additionally, images with sunglasses are processed with a reconstruction network which has been trained to learn to reverse such modifications. This is because obfuscating the eye region has been observed in the literature to have the highest impact on the accuracy of face detection or recognition.

We start from the popular Labeled Faces in the Wild (LFW) database, to which we apply the different modifications, generating 8 datasets, each one containing one particular modification. Each dataset contains 4,324 images of size 64 x 64, with a total of 34,592 images. The use of a public and widely employed face dataset allows for replication and comparison. We also include the original (unfiltered) images to allow other researchers to incorporate new filters of their choice, or to train different image reconstruction methods.

![sample_images_filters](https://user-images.githubusercontent.com/6042693/157897137-d9f55f12-70a0-4af0-8de6-b8666520e1f7.png)

# Usage
  - Download the compressed files (13 in total) and uncompress them
  - **Please cite reference 1) below in your publications if you make use of the data of this repository**

# People & Contact
  - [Fernando Alonso-Fernandez](http://wiki.hh.se/caisr/index.php/Fernando_Alonso-Fernandez)  (contact person).

# References
  1) Hedman, P., Skepetzis, V., Hernandez-Diaz, K., Bigun, J., Alonso-Fernandez, F., "On the Effect of Selfie Beautification Filters on Face Detection and Recognition" [https://arxiv.org/abs/2110.08934]()
  2) Hedman, P., Skepetzis, V., The Effect of Beautification Filters on Image Recognition: "Are filtered social media images viable Open Source Intelligence?" Master Thesis at Halmstad University, Sweden (Master’s Programme in Network Forensics) [http://urn.kb.se/resolve?urn=urn:nbn:se:hh:diva-44799](http://urn.kb.se/resolve?urn=urn:nbn:se:hh:diva-44799)
  
<a href="https://zenodo.org/badge/latestdoi/468794479"><img src="https://zenodo.org/badge/468794479.svg" alt="DOI"></a>
