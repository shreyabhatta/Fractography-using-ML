# ML-Based-Fractography
# Problem Statement :
To classify metal fracture into brittle or ductile through image classification and machine learning on SEM images.

# Foreground : 
Fracture in metals is one of the most important reasons behind the failure of engineering components and structures. Fracture in metals has lead to catastrophic failures in steel buildings and bridges , oil, and gas pipelines , automobiles and aerospace structures . Ductile fracture and Brittle fracture are the most common types of fracture in metals under monotonic loading conditions . A decision about the choice of a suitable damage model to simulate the failure depends on the type of fracture as the basic microscopic damage mechanisms leading to the fracture varies from one fracture type to another. Both ductile and brittle fracture zones are observed in structural steels, dual- and multiphase steels, aluminum, and titanium. The choice of damage model in the case where multiple fracture mechanisms are involved depends on fracture initiation mechanism, the dominant fracture mechanism and/or the conditions under which the fracture transitions from one type to another type.

Brittle Fracture is a condition that occurs when a material is subjected to temperatures that make it less resilient, and therefore more brittle. The potential for material to become brittle depends on the type of material that is subjected to these low temperatures. Some materials, such as carbon and low alloy steels will become brittle at low temperatures and therefore susceptible to damage ranging from cracking to shattering or disintegration of equipment.

Ductile fracture is the material failure that exhibits substantial plastic deformation prior to fracture. The ductile fracture process is slow and gives enough warnings before final separation. Normally, a large amount of the plastic flow is concentrated near the fracture faces.

![image](https://user-images.githubusercontent.com/84590255/178829456-607b0385-5697-4c12-a726-35cc2cc29527.png)                    ![image](https://user-images.githubusercontent.com/84590255/178830893-bd76f63b-4a85-4cf4-ada4-0be94e498a0a.png)

Although the fracture type can be determined based on the mechanical and microstructural properties of a metal and state of stress and strain, a visual inspection of fractographic images is often conducted to identify the fracture type of metal. Although simple, visual inspection is slow, prone to confirmation bias and cannot be used for quantitative analysis of fracture surfaces. For instance, the evaluation of dominant fracture type and description of the visual characteristics of fracture surfaces is not possible through visual inspection. 

Through this project, we aim to determine efficient methods and useful parameters for classification between these two types of fractures.

# Progress :
1. Explored texture analysis methods like Gray-level histograms, Gray-level difference, Gray-level co-occurence matrix, Run length matrix, Fourier transofrm etc.
2. Explored new methods like calculation of fractal dimension by using algorithms like differential box counting method.
3. Used various filters and image processing techniques like Hough transform, Canny edge detection, etc. 

# Challenges :
1. Determining proper parameters for these methods, like homogeneity, correlation, entropy, contrast, etc.
2. Identifying the method best suited to extract relevant features for distinguishing the images.

# References :
