# Image Filter using GANs Capstone
## Introduction 
Digital image processing is very prevalent in society today and only continues to grow as society spends more and more time online. The creation and application of image filters play a crucial role in enhancing and manipulating images for various purposes. Filters have wide-ranging applications in several industries. Examples include, but are not limited to, social media, video/photo editing software companies, design, telecommunication, technological companies, security, etc. 
## Goal/Problem
The goal of this project is to explore and develop an image processing filter that manipulates the individual components of an image, while enhancing the quality, aesthetics, and utility. Training and implementing filter techniques using GANs, while addressing specific image processing requirements, will give way to more opportunities to discover how to improve digital image transformations. Generating a one-shot fast learned image filter that alters image attributes to transform to a certain style, while simultaneously minimizing undesirable distortions, creates a valuable manipulation that can be used by all people and industries. 
## Overview
Using PyTorch as the neural network framework, this code uses one-shot learning techniques and GAN inversions that fine-tune a pre-trained StyleGAN with only one example of a particular image style. Essentially, the process learns a style mapper from only one reference style image, which is beneficial because collecting data sets per style would be too time consuming. StyleGANs learn image to image translation fairly fast with a relatively small dataset, but obtaining a small dataset per different style would be difficult; therefore, utilizing this code’s method results in faster and more quality results. Final report thoroughly explains details about generator, discriminator, predictor, training, fine-tuning code and processes. 
## Results
My results were very pleasing. The generated image looks similar to the original and depicts the watercolor brush strokes very clearly. The colors and facial positioning of the two images are also constant. In addition, I tested some random faces from the database onto my reference style to see how they did and these were also very accurate. However, there could be some further fine tuning steps to implement because as shown in the fourth random sample, the outline of their face is very blurry. It is unclear why only that photo transformed that way, but based on my research it might have to do with the background lighting being too light colored and blurred. 
## Future Work 
Therefore, for further work, I could strive to fine-tune the styleGAN to prevent this obscure blur from occurring. I would love to keep working on this project to improve the accuracy and generate other styles that can be used for individuals and companies. Additionally, my project was geared towards a more technical audience because I was focused on learning the implementation and structural components of Generative Adversarial Networks. However, continuing forward, I want to create a website or application that implements my project and makes it possible for non-technical individuals to use for their benefits. 
## Citation/References
Code borrowed from JoJoGAN and e4e github repositories. 

@article{chong2021jojogan,
 	 title={JoJoGAN: One Shot Face Stylization},
 	 author={Chong, Min Jin and Forsyth, David},
 	 journal={arXiv preprint arXiv:2112.11641},
 	 year={2021}
}
