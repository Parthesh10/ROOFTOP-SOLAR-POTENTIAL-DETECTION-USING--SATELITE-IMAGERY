# ROOFTOP-SOLAR-POTENTIAL-DETECTION-USING--SATELITE-IMAGERY

As we know nonrenewable energy is not a good thing to be dependent on it because of its harmful
effect on the environment caused by the greenhouse gases and now we can also see the rising cost 
of the petrol a fossil fuel. So, what we can do about it? we can try to shift our attention towards 
the renewable source of energy. This is where we come into picture we are finding the potential 
surface area on rooftops to install photovoltaics (PV) panels which can be really useful because 
of solar energy and calculating the solar energy generated by a particular area.

We are achieving this by applying Machine Learning techniques with satellite and aerial imagery, 
will help in bypassing the limitations of surveys in providing the surveys in providing this 
mapping at large scale. Being more specific we are using convolutional neural network to describe 
available rooftop area on which we can install photovoltaics (PV) panels by the method of pixel 
wise segmentation. We picked up the dataset form the Kragel which was labelled. We tried 
different data augmentation by flipping data 90 degrees, rotating it in order to increase the model 
performance. After training our model on the dataset we are able to detect the rooftop with the 
accuracy on the test set of about 90.33% and an Intersection over Union (IoU) of 55.65% with 
only 245 images in the training dataset. In future our model will able to predict the available 
rooftop area with more accuracy and on different geographical locations as we know different 
geographical location have different style of rooftops so we have to train our model on that type 
of data then it will able to predict the available rooftop area.
