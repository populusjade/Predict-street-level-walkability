# Predict-street-level-walkability
The project use pre-trained semantic segmentation model to calculate proportion of built environment variables and use regression models to determine a correlation between built environment variables and walking preferences 

The first compoenent of the project aim to transform geo location infor from GIS file to coordinates which can be used to receive street view images with API key.

The second component use pre-trained semantic segmentation models to detect the built environment variables and save the pixels of variables in csv file.

The third component use different regression models to determine the correlation between different built environment variables and labels(based on survey results from Helsinki city)

If you use this code, please consider cite as the following: 
Yang, J., Fricker, P., & Jung, A. (2022). From Intuition to Reasoning: Analyzing Correlative Attributes of Walkability in Urban Environments with Machine Learning. Journal of Digital Landscape Architecture, 2022(7), 71-81. https://doi.org/10.14627/537724008
