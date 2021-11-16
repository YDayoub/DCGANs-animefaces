# DCGANs-animefaces
This repo contains notebook implementation of DCGANs on animefaces dataset from [Laurence Moroney](https://laurencemoroney.com/about.html).  
The main features of DCGAN
* Use convolutions without any pooling layers
* Use batchnorm in both the generator and the discriminator
* Don't use fully connected hidden layers
* Use ReLU activation in the generator for all layers except for the output, which uses a Tanh activation.
* Use LeakyReLU activation in the discriminator for all layers except for the output, which does not use an activation.

**Note**: I didn't tune the parameters to give the best performance. So, you may want to spend some time tuning them.