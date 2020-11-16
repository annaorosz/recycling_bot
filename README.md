**ML System design for a Recycling bot**

The goal of the [Recycling bot](rb.pdf) project was to design the architecture of an object detection and classification system.

The recycling bot is be able to *detect* and *classify* trash from a conveyor belt and sort them into recycling buckets of paper, plastic, glass and metal. 

The problem was split into two main tasks: first, to detect the object and calculate the steps to pick it up and secondly to collect visual and sensory data to classify the object, which was achieved by a set of different sensors as well as a series of CNNs and finally a Fully Connected NN to output a softmax corresponding to the final ouput of the model.

Furthermore, the project also discusses the necessary hardware and software tools required for the recycling bot.

