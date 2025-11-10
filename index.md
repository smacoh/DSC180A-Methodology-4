# Samuel Cho (sjc006@ucsd.edu)

Understanding deep learning through feature learning (A14) - Tianhao Wang

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered in my domain this quarter is grokking. Grokking is a surprising phenomenon in which a neural network undergoes an abrupt transition from poor generalization to achieving near-perfect validation/test accuracy. This transition occurs long after the model has already memorized the training data and achieved perfect training accuracy. It is interesting because it defies previous conventions about overparameterized neural networks, in which they were expected to overfit to the training data and consequently fail to generalize. Understanding grokking can provide insights into the behaviors of neural networks and guide future research and design regarding model generalization and the training process.  

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A potential investigation I would like to pursue for my Quarter 2 Project is accelerating grokking. In other words, I would like to investigate how to reduce the time needed for grokking, or the sharp generalization transition to occur. Successfully accelerating this process and understanding the principles behind this acceleration could lead to more efficient training algorithms that reliably achieve high generalization without the need for extensive training, reducing computational costs and potentially enabling the development of more robust and efficient AI models.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A potential change I would make to the approach taken in my current Quarter 1 Project is to focus more on building off of previous works, testing new approaches on top of reproducing the initial results. This could be exploring its theoretical implications or understanding the conditions required for grokking to emerge in different situations, for example.

**4. What other techniques would you be interested in using in your project?**

Some other techniques I would be interested in using in my project are using different optimizers, such as SGD or AdamP, to see how they affect grokking, and measuring sharpness to quantitatively track the model's memorization and generalization states.
