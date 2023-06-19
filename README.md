# ImageInPainting
This is a computer vision project. The topic of this project is portrait image restoration using Generative Adversarial Networks.


Facial inpainting is a process
restore the missing, damaged parts in the leg image
content, creating reasonable face structures for affected pixels
lack. This is a challenging task in which regions
missing must be filled based on visual data (visual
data) is available. The previous methods only extracted the
information from a single image and often produces results that do not
satisfactory due to lack of high level context.
Recently, the input data adjustment method is available
research and application to image recovery problems
gives very good results. To better understand this method,
Our team implements data models that have
the ability to generate new data (generative model). Progress
done, we proceed to encode the input image as
unrecovered images using the term
image scene and previous image losses, encoding
This is then passed to a model capable of generating data
new data through a generative adversarial
networks) to recover the missing portion of the image.
Based on CelebA dataset with over 200,000 images
Portraits vary in poses and background variations. In
In this study, we hope to restore the content of
missing content of the image, successfully predicting information
in large missing regions and achieve the present image state
photorealism.
