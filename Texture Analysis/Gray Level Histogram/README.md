# GRAY LEVEL HISTOGRAM

The gray-level histogram is an analysis tool that examines the distribution of pixel values in an input image.

A grey level histogram indicates how many pixels of an image share the same grey level. The x-axis shows the grey levels (e.g. from 0 to 255), the y-axis shows their frequency in the image. 

Gray-level histogram presents the frequency of l . We let the probability of l be P(l), and from P(l) , we obtain the following seven features.  

https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true

- μ and σ are the average and the variance of the pixel value in the target image, respectively.
- If the histogram is biased toward higher, contrast shows higher. 
- If the histogram is asymmetric, skewness becomes higher. 
- Kurtosis shows how much the histogram is concentrated around μ . 
- The larger a particular P(l) is, the larger the energy; conversely, entropy takes on a larger value the larger the various P(l) are.
