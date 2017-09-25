### Scan through a GFP or RFP image, identify foci

This program creates an n by n kernel to run over our 512 x 512 images. A reasonably safe bet (for now) is that each focus will fit into a 5 x 5 kernel (n=5). 

It goes over each pixel, draws the kernel around it, and then applies one of several scoring functions to assign each pixel a score. This score represents its probability of belonging to a focus.


