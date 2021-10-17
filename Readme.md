Automating processing of DEM and slope, aspect and hillside files to
into a relief representation inspired by the original Lehmanns's method.
Inspired by the blogpost: 



[Code with whole procedure is here](Lehmanns_Shrafure.ipynb) <br>
<link>

Several parameters: <br>
- number of contours, <br>
- distance between sampling points on contours<br>
- multiplier factor (each line length is calculated based on a slope at point, multiplied by the multiplier factor)
<br>should be manually adjusted to fit the terrain and relief characteristics

Final map for the Tatra mountains area looks like this:
![](results/tatras.png "Title")


