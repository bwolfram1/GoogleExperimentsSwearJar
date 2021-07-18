# GoogleExperimentsSwearJar
This is a tensorflow powered swear jar. Can only classify shit and fuck but will add $0.50 to the swear jar each time it detects either swear word. 

I used Edge Impulse to train, test, and deploy the model. Also, the code is from the example code but modified. 

Below is the serial output. 
![serial output](https://github.com/bwolfram1/GoogleExperimentsSwearJar/blob/5a9e3e92797cbfb0f15db37ed9ef3c75bc35b6f5/assets/Screen%20Shot%202021-07-18%20at%204.54.31%20PM.png)


If you wanted to see the prediction percentage then you can set debug_basic to true and you will get this:
![seral debug](https://github.com/bwolfram1/GoogleExperimentsSwearJar/blob/4205cde6ec3e6c8918ea408efcca99fa2c54846c/assets/Screen%20Shot%202021-07-18%20at%205.01.55%20PM.png)

Here is an example of the class training accuracy. 
![training results](https://github.com/bwolfram1/GoogleExperimentsSwearJar/blob/5a9e3e92797cbfb0f15db37ed9ef3c75bc35b6f5/assets/Screen%20Shot%202021-07-18%20at%204.57.07%20PM.png)
