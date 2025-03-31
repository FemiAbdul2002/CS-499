Name: Femi Abdul
 Course: CS 499
 Assignment: Milestone Three – Algorithms and Data Structures

Artifact Narrative: Pirate Intelligent Agent – Algorithm & Data Structure Enhancement
The artifact I selected for my Algorithms and Data Structures enhancement is the Pirate Intelligent Agent project, originally developed in CS-370: Artificial Intelligence. 
The project is a reinforcement learning model that navigates a maze to find treasure while avoiding traps. It uses a Q-learning algorithm with neural network support to make decisions and optimize its policy over time.

I included this artifact in my ePortfolio because it is an excellent demonstration of my understanding of algorithm design, decision-making logic, and data structure use in machine learning environments. 
The implementation of Q-learning showcases a real-world application of algorithmic problem-solving, which is critical for modern AI solutions. My enhancements focused on improving the algorithm’s training 
efficiency, exploration-exploitation strategy, and data storage structure for the Q-table.

The core enhancement I implemented was optimizing the qtrain() function to improve how the agent learns over time. Specifically, I introduced a decaying epsilon value in the epsilon-greedy strategy, 
which improves learning convergence by reducing randomness as training progresses. I also added a dynamic learning rate (alpha) to allow the agent to make larger updates early in training and smaller ones later, stabilizing learning outcomes.

In addition, I restructured how Q-values were stored by modularizing the Q-table as a class object. This change improved the readability and scalability of the algorithm. 
While the project still uses in-memory storage for now, the structure is now ready for future integration with persistent storage like a database or JSON file something I plan to implement in Milestone Four.

I met the course outcome related to designing and evaluating computing solutions using algorithmic principles. The logic enhancements I made clearly reflect algorithmic thinking and demonstrate trade-offs 
in balancing learning speed with model stability. I also believe I have partially met the course outcome regarding the use of innovative techniques and tools, especially through the modularization and abstraction of logic within the Q-learning loop.

During this enhancement, I deepened my understanding of reinforcement learning theory, especially how fine-tuning algorithm parameters significantly impacts performance. One challenge I faced was maintaining 
balance between exploration and exploitation finding the right pace for decay was tricky. I overcame this by researching best practices and testing various decay strategies. Another challenge was ensuring 
modular design didn’t interfere with the model’s performance. Through testing and validation, I confirmed that the modular Q-table improved maintainability without hurting accuracy.

This enhancement makes the artifact a much stronger representation of my ability to work with real-world algorithms and improve them iteratively. It also reinforces my readiness to contribute to AI and machine 
learning applications that demand algorithmic efficiency and logic design.


