# TrainingAssistant

Hall-Effect sensors can be used to build a retrofit system which can be attached to conventional weight training machines. Using an array of Hall-Effect sensors the position over time of the weight can be recorded by having a magnet attached to the moving weight stack disc(the top one). The Hall-Effect sensors measure the presence of a southpole and with a known position of the sensors the position-time relationship can be measured. Mechano-biological descriptors for weight training such as time under tension or the number of repetition can be extracted from the position-time measurement series.

Using a pull-up or pull-down resistor of 10 k Ohm the Hall-Effect sensors can be attached to the GPIO pins of a Raspberry or a ESP3288 NodeMCU to build an IoT solution. For the counting of the weight stacks used during the training a magnet can be attached to each weight disc. In addition Hall-Effect sensors can be used to count the weight discs which stand still during training. Using this information the weight used during training can be calculated. With a Multiplexer the number of GPIO pins needed can be drastically reduced.

The whole approach is described in my Master Thesis (zhaw, April 2020).
