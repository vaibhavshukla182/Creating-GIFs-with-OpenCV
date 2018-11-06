# Creating GIFs with OpenCV

We are going to create animated GIFs with OpenCV, dlib, and the ImageMagick toolbox.

## Prerequisites:

You are advised to create a conda environment before proceeding ahead, its not compuslory but it would be better.

    conda create -n gif python anaconda
    source activate gif
   
    pip install opencv-python
    pip install dlib
    brew install imagemagick
    pip install imutils
    
Make a new folder 'meme',in it do:
    
    git clone https://github.com/vaibhavshukla182/Creating-GIFs-with-OpenCV.git
    cd meme
    
## To run the python file type:
      
    python create_gif.py --config config.json --image images/me.jpg --output me.gif
    
  
Building a Deal With It meme generator using OpenCV can teach us a number of valuable techniques used in practice, including:

1)How to perform deep learning-based face detection.

2)How to use the dlib library to apply facial landmark detection and extract the eye regions.

3)How to take these two regions and compute the rotation angle between the eyes.

4)And finally, how to generate animated GIFs with OpenCV (with a little help from ImageMagick).


In order to build our meme generator, we leveraged computer vision and deep learning in a number of practical ways, including:
- Face detection
- Facial landmark prediction
- Extracting regions of the face (in this case, the eyes)
- Computing the angle between the eyes, a requirement for face alignment
- Generating transparent overlays via alpha blending
