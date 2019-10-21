# Quantum Futures Hackathon-2019

This is an overview of my team's work at the Quantum Futures Hackathon hosted by CERN and the Quantum Open Source Foundation (QOSF) in Toronto.
From starting from having no experience with quantum programming and creating basic quantum circuits to recreating a professional research experiment in 3 days, it was an incredible experience!

With access to [Rigetti's quantum simulators](rigetti.com), we recreated an experiment to compare clustering algorithms on classical computers vs. quantum computers. 
Our approach used the Iris dataset and the algorithms distinguished between two species of flowers from their petal and stem lengths. 

### Classical Approach
Using the [k-means clustering algorithm](Quantum-Futures-Hackathon-2019/Classical ML Clustering.py) , we were able to achieve 100% accuracy in clustering 8 data samples in a time of 35.7 ms on a local CPU. 

### Quantum Approach
Using Rigetti's Quantum Optimisation Approximation Algorithm (QAOA) and a Maxcut clustering technique, we were able to achieve 100% accuracy in clustering 8 data samples in a time of 92,000 ms on Rigetti's [Quantum Virtual Machine](Quantum-Futures-Hackathon-2019/QML Clustering.py).

Obviously, this isn't ideal and shows us the long ways to go still with quantum computing. That being said, I had an amazing time learning about the fundamentals of this growing technology and would like to thank CERN, the QOSF, and the Creative Destruction Lab (CDL) for bringing about this opportunity. 
And of course, none of this would have been possible without our talented mentors from ProteinQure - Mark FingerHuth and Tomas Babej.

If you have any questions about my work or would just like to connect in general, feel free to reach out on [Linkedin](https://www.linkedin.com/in/madhav-malhotra/)!
