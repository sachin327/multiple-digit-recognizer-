# multiple-digit-recognizer
  
 # Here i am using sliding window technic to select all the possible part of image and checking for actual image vs background image. Then if it is not a background image then passing it to another model which detect its value(digit no. 0 to 9).After that using IOU and NON MAX SUPPRESION eleminate all unwanted predictions we have our final output image.
 
  
# Input image
  

  ![alt text](https://github.com/sachin327/multiple-digit-recognizer-/blob/master/images/input.png)

# First we have to change our input image according to our training image(MNIST DATASET)
  

  ![alt text](https://github.com/sachin327/multiple-digit-recognizer-/blob/master/images/convert_mnist.png)
  
# After passint this image to our model we got this image

  

  ![alt text](https://github.com/sachin327/multiple-digit-recognizer-/blob/master/images/without_NMS.png)

# Now we apply NMS to our image then got the final output image

  

  ![alt text](https://github.com/sachin327/multiple-digit-recognizer-/blob/master/images/output.png)
