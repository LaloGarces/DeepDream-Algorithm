# DeepDream-Algorithm

## In this colab notebook, I use TensorFlow to experiment with AI Art, in specific with the Deep Dream Algorithm. Use it as you wish, try it with your own images! 🙂
 
### I included some comments to understand what's happening under the hood; Hope you find it useful!  🙌

#### Important points to mention

- The original file code is too heavy due I ran 7,000 steps with step_size = 0.001, to get a great Deep Dream style image 😅 :
![This is an Image](https://raw.githubusercontent.com/LaloGarces/DeepDream-Algorithm/main/Pictures/Final%20Results%20Image.png)
- So, I'm going to put in #comments the last part of the code where I run the algorithm, to be able to upload the colab here in Github.
- Remember, just remove the #comments in the last part of the algorithm to run on your side. 
- I'm including the original images if you want to run the model with the same images that I used. 
- The original images were developed by me with [Stable Diffusion](https://github.com/CompVis/stable-diffusion)

## Install

```
pip install numpy==1.19.5
```

**Important:** At the end of the code in the part where we're going to use Deep Dream, you need to run this code to don't get en error at the moment of fitting your image in the model. 
