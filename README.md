Generally DL models are blackboxes ie. we cant really see the internal workings due to the presence of millions of parameters
But to see understand the working of CNN's we can see the output of our CNN model after each layer ie. what is done here 
Initially what we did was seeing how our filters looked at layer 1 it has 64 filters but we printed some of them 
Now see the output of layer 1 we can see how first layer is capturing simple simple features like face edges, hair edges, face outlines, beard outlines etc.
Now as we go deeper we can see the identity of our image starts getting lost as now its not focusing on small small features but trying to figure out as a whole what the provided image is
going more deep it is figuring out specific spots of the image and understanding the spatial(linear) relation between them 
Then spots when combined together we somewhat get the image we gave it to classify 
