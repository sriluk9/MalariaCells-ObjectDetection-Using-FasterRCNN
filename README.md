# MalariaCells-ObjectDetection-Using-FasterRCNN

https://data.broadinstitute.org/bbbc/BBBC041/

https://arxiv.org/abs/1804.09548

Deep learning based models have had great success in object detection, butthe state of the art models have not yet been widely applied to biologicalimage data. We apply for the first time an object detection model previouslyused on natural images to identify cells and recognize their stages inbrightfield microscopy images of malaria-infected blood. Many micro-organismslike malaria parasites are still studied by expert manual inspection and handcounting. This type of object detection task is challenging due to factors likevariations in cell shape, density, and color, and uncertainty of some cellclasses. In addition, annotated data useful for training is scarce, and theclass distribution is inherently highly imbalanced due to the dominance ofuninfected red blood cells. We use Faster Region-based Convolutional NeuralNetwork (Faster R-CNN), one of the top performing object detection models inrecent years, pre-trained on ImageNet but fine tuned with our data, and compareit to a baseline, which is based on a traditional approach consisting of cellsegmentation, extraction of several single-cell features, and classificationusing random forests. To conduct our initial study, we collect and label adataset of 1300 fields of view consisting of around 100,000 individual cells.We demonstrate that Faster R-CNN outperforms our baseline and put the resultsin context of human performance.

Metric : Mean Absolute Precision

Losses : 
RPN(Region Proposal Network) Classification & Regression Losses
R-CNN classification & Regression Losses
