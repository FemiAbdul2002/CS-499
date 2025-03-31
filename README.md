**Artifact Enhancement Narrative: Software Design and Engineering

**Name:** Femi Abdul  
**Course:** CS 499 – Computer Science Capstone  
**Enhancement Area:** Software Design and Engineering  



### Description of the Artifact

The artifact selected for this enhancement is the "Pirate Intelligent Agent" project developed in CS-370: Artificial Intelligence. Originally built as a reinforcement learning simulation, the project trains an AI-powered pirate to navigate a maze and find a hidden treasure while avoiding traps. The original version focused on building a basic Q-learning algorithm to help the agent learn optimal movement strategies.



### Why This Artifact Was Chosen

I chose this artifact because it demonstrates a solid foundation in AI behavior modeling and provides a strong opportunity to enhance software design through better structure, modularity, and maintainability. It also ties directly into areas where I want to grow professionally—AI and machine learning—and highlights my ability to take a conceptual model and implement it in code.



### Enhancements Made

Several improvements were made to align this artifact with professional software engineering standards:

- **Modularization:** The Q-table functionality was moved into a separate class, improving readability and separation of concerns.
- **Documentation:** Docstrings and inline comments were added throughout the code to explain the logic behind functions and variable choices.
- **User-Friendly Output:** Console outputs were reformatted to improve clarity during training.
- **Epsilon-Greedy Strategy:** Implemented epsilon decay to improve learning efficiency over time.
- **Dynamic Learning Rate:** Introduced a decaying learning rate to stabilize training.

These enhancements made the code easier to maintain, reuse, and scale.



### Skills and Abilities Demonstrated

- **Code organization and refactoring** using object-oriented design principles
- **Improved readability and commenting** for better team collaboration
- **Advanced control over AI training parameters** to fine-tune learning performance
- **Preparation for future database integration** by abstracting Q-table logic into a separate module



### Reflection on the Learning Process

Enhancing this project gave me deeper insights into how structured software design leads to more maintainable and scalable AI solutions. Initially, the code worked but lacked modularity and clear boundaries between logic layers. By breaking the system into classes and methods with specific responsibilities, I gained experience working closer to how production AI systems are architected.

One of the main challenges was ensuring that the restructuring of the code didn't interfere with its performance. I had to test the agent’s performance thoroughly after each change to ensure that learning behavior remained consistent. Another challenge was tuning the epsilon and learning rate decay formulas so that they didn't prematurely reduce exploration or halt learning too early. After research and iteration, I found balanced decay rates that resulted in improved overall performance.

This artifact, now improved through better design and structure, stands as a strong example of my capabilities in software design and engineering, particularly in AI development contexts.



