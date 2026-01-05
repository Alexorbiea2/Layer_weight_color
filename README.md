To use the shader

1 Download **Layer_weight_color.blend**  
2 In Blender go to **File -> Append**  
3 Select **Layer_weight_color.blend**  
4 Open the **NodeTree** folder  
5 Pick **Layer_weight_color** and click **Append**  
6 Go to the **Shader Editor**  
    If there is no material add a new one  
7. In the Shader Editor do **Add -> Group -> Layer_weight_color**  
8. Delete the old **Principled BSDF** and **Material Output** nodes  

The shader will now be active.  

If you want to edit the shader right click on the node and choose **Ungroup** or press **Ctrl + Alt + G**

Designed for **Eevee** but probobly works in Cycles too
Made in blender version **5.0.1** 
