# music_neural_net

I want to see if an adversarial neural network can be used to generate music sound files.

The first step is to develop a way to generate a corpus of training data for the discriminative model. I will start by using recordings of piano music of Sergei Rachmaninov. These will be broken into chunks of random length between 5 and 10 seconds, starting from a random point, with a random amount of compression applied within a reasonable range. My hope is that this way I will be able to “bootstrap” enough data to be extracted to prevent overfitting. This data will not be stored, but rather will be generated on the fly and loaded into the model. 

I will try to do this using Python. 

Inspiration: Generative Adversarial Nets, Goodfellow et al. 2014

http://www.github.com/goodfeli/adversarial


 
