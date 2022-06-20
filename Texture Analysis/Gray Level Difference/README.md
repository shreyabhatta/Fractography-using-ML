# GRAY LEVEL DIFFERENCE

The gray-level-difference statistic is an analysis tool that examines the difference between the pixel of interest and its neighbors. Like a gray-level histogram, it calculates the distribution of the difference. 

In the target image, we consider pixel pair (i,j) . Pixel j is in a position to pixel i that is direction θ and range r. Pixel values of pixel i and j let li and lj , and difference l′ are defined as follows: 

l’ =| li - lj | 

We defined probability Pδ( l’) as difference statistics, where δ=(θ,r).

P(l) is replaced to Pδ( l’) , and seven features of δ are calculated. Features are calculated for each δ , and we let their averages with respect to δ be seven features of Gray-level difference. 
