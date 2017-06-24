## Application of using instanced rendering on OpenGL

Generally, it is not hard to load models and texture-mapping on nodels if we have appropriate models and textures.    
In this project, I simulated a difficulat situations: how to make objects vivid without suitable textures? and how to create many objects once ?     

There are three levels in this tree. I used many group of leves in each level. In the top level, there was only one group of level, but in the second level, there were 15 group of leaves, and there were 25 group of leves in the third level. Each group of leaves had 100 amount of leaves. 
### Type 1 
Leaf model(no textures) with basic lighting in type 1. Because the leaf model was very large, I had to shrink the leaf model many time. In order to let program run fast. I only used leaf model and basic lighting. Here, the basic lighting, including ambient, diffuse, and specular is for showing the shape of leaves.     
<img width="700" alt="screen shot 2017-05-25 at 4 57 35 pm" src="https://cloud.githubusercontent.com/assets/16565587/26478410/e65f83ae-4180-11e7-9ad4-26cafd1ea89e.png">

### Type 2 
leaf model and a bump texture in type 2.
<img width="700" alt="screen shot 2017-05-25 at 7 10 29 pm" src="https://cloud.githubusercontent.com/assets/16565587/26478425/0718dfa0-4181-11e7-9fdd-4e38874bcef3.png">

### Preject demo
The leaves shapes appear by the timing.

![download](https://cloud.githubusercontent.com/assets/16565587/26479241/9addf5e0-4186-11e7-98f8-117a50b9b30d.gif)
