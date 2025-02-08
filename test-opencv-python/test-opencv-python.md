```python
import cv2
```


```python
import matplotlib.pyplot as plt
```


```python
import numpy as np
```


```python
pwd
```




    '/home/roc/cmake'




```python
img = cv2.imread("../228980_icon.jpg")
img = cv2.cvtColor(img, cv2.COLOR_BGR2RGB)
img.shape
```




    (32, 32, 3)




```python
type(img)
```




    numpy.ndarray




```python
plt.imshow(img)
plt.axis("off")
```




    (-0.5, 31.5, 31.5, -0.5)




    
![img](output_6_1.png)
    



```python

```
