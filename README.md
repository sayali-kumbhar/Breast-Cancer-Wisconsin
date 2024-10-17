Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.<br>


Attribute Information:<br>

1) ID number<br>
2) Diagnosis (M = malignant, B = benign)
3-32)
<br>
Ten real-valued features are computed for each cell nucleus:<br>

a) radius (mean of distances from center to points on the perimeter)<br>
b) texture (standard deviation of gray-scale values)<br>
c) perimeter<br>
d) area<br>
e) smoothness (local variation in radius lengths)<br>
f) compactness (perimeter^2 / area - 1.0)<br>
g) concavity (severity of concave portions of the contour)<br>
h) concave points (number of concave portions of the contour)<br>
i) symmetry<br>
j) fractal dimension ("coastline approximation" - 1)<br>

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
<br>
All feature values are recoded with four significant digits.<br>

Missing attribute values: none<br>

Class distribution: 357 benign, 212 malignant<br>
