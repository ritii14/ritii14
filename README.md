# Welcome! 👋  

Hi there! I'm Riti.  
I'm an undergraduate student in Computer Science & Engineering at IIT Delhi. Passionate about Artificial Intelligence, Societal Computing, and Human-Computer Interaction, I'm constantly exploring how technology can positively impact society.

## Current and Past Projects
- **Bird Species Classification with CNN**
  - Dataset: Used a dataset with images of 10 bird species, ranging from 500 to 1,200 images per species.
  - Model: Built a CNN with convolutional layers, max pooling, dropout, and fully connected layers for classification.
  - Data Preprocessing: Applied transformations like rotation, flipping, and resizing using PyTorch’s DataLoader to make the model robust.
  - Training & Evaluation: Trained using Adam optimizer and CrossEntropyLoss, achieving good accuracy on the test set.
  - Model Management: Implemented model saving (save the best model) and loading functions for reusability.
  - Libraries: Utilized PyTorch, torchvision, and scikit-learn for dataset handling and deep learning tasks.
 
- **VAE and GMM-Based Image Classification and Reconstruction with PyTorch**
  - Implemented a Variational Autoencoder (VAE) for image reconstruction and dimensionality reduction.
  - Designed an encoder-decoder architecture using multi-layer perceptrons (MLP) for latent space representation.
  - Optimized VAE model using Adam optimizer and ReduceLROnPlateau scheduler for adaptive learning rates.
  - Integrated a custom dataset loader to filter and preprocess specific image classes from an NPZ file.
  - Implemented custom loss function combining binary cross-entropy (BCE) and Kullback-Leibler divergence (KLD) for VAE training.
  - Extracted latent vectors and trained a Gaussian Mixture Model (GMM) on the latent space for clustering. Evaluated GMM clustering performance using accuracy, precision, recall, and F1-score metrics. Used structural similarity index (SSIM) to evaluate the quality of reconstructed images.
  - Utilized PyTorch for deep learning model training, and sklearn for Gaussian Mixture Model implementation. Visualized GMM clusters with ellipses in latent space for intuitive understanding of cluster distributions.
  - Implemented save and load functionality for both VAE model parameters and GMM parameters.
 
- **Game Playing AI Agent for Havannah**
  - Developed an AI agent for the Havannah game using minimax algorithm with alpha-beta pruning to efficiently explore possible moves.
  - Heuristic Evaluation: Designed a custom heuristic to evaluate moves based on reachability, proximity to key board areas (corners/edges), and Euclidean distance. The heuristic enhances the AI’s ability to prioritize moves that strengthen its position on the board.
  - Minimax Algorithm: Applied the minimax strategy to simulate opponent and AI moves, ensuring the agent chooses the optimal move based on a recursive search of possible future states. Integrated alpha-beta pruning to optimize the search process by pruning suboptimal branches, significantly improving performance and reducing computation time.
  - Optimized Performance: Utilized a depth parameter to control the search depth for the minimax algorithm, optimizing AI performance based on time constraints.

- **ASR Error Correction Agent Using Search-Based Algorithms**
  - Developed an ASR error correction agent that utilizes search-based algorithms to improve text accuracy in voice-enabled applications.
  - Implemented Local Beam Search to correct errors in ASR outputs by exploring different text transformations, including phoneme substitutions and word insertions. Used a phoneme table and vocabulary to generate potential neighboring states for ASR correction, optimizing the search process for better results.
  - Applied a cost function based on text similarity (OpenAI Whisper model) to guide the search for the most coherent and accurate sentence, comparing generated states to a reference sentence.
  - Developed the search agent with two phases: Phase 1 focused on phoneme substitution, and Phase 2 used word insertion to further refine the ASR output. Optimized the algorithm for efficiency, using beam search to explore the search space and prioritize the most promising corrections based on their cost.
 
- **Client-Server Communication with Protocols and Scheduling**
  - Client-Server Communication: Implemented TCP-based communication between a word-counting client and a server. Developed both client and server applications using C++ for efficient data transmission and processing.
  - Concurrency Handling: Managed concurrent client-server connections, ensuring efficient communication while addressing server limitations in handling multiple requests.
  - Distributed Protocols: Implemented multiple distributed communication protocols, including:
    - Slotted Aloha Protocol
    - Binary Exponential Backoff (BEB)
    - Sensing and BEB
  - Performance Analysis: Conducted experiments to measure the completion time based on different protocol configurations, number of clients, and network conditions.
  - Server Scheduling Policies: Implemented and tested server scheduling strategies, including FIFO and Fair Scheduling to prioritize and manage client requests efficiently.
 
- **Network Controller and Routing Solutions Development**
  - Network Controller Development: Developed both Hub Controller and Learning Switch for network traffic management, using Ryu Controller framework for OpenFlow-based networking.
  - Switching Mechanisms: Implemented Hub Controller that forwards traffic to all switch ports and Learning Switch that installs flow rules based on MAC-to-Port mappings.
  - Spanning Tree Protocol (STP): Implemented a spanning tree algorithm to handle network cycles and prevent broadcast storms, ensuring loop-free topology.
  - Shortest Path Routing: Developed a controller application for shortest path routing in an L2 network, with link weights based on capacities to optimize routing performance.
  - Congestion-Aware Routing: Extended shortest path routing to dynamically adjust routes based on current link utilization, simulating real-world congestion-aware routing behavior.
  - Topology Simulation: Worked with network topology files and used a Python-based Ryu controller to simulate and test various network behaviors.
 
- **Network Programming and Congestion Control Algorithms Implementation**
  - Implemented UDP Reliability Mechanisms: Developed mechanisms for reliable data transmission over UDP, including cumulative acknowledgments (ACKs), retransmissions, and fast recovery using duplicate ACK detection.
  - Designed and Implemented Timeout and Packet Numbering: Integrated timeout mechanisms and sequence numbering to ensure correct packet delivery and reconstruction in a client-server communication model.
  - Implemented Sliding Window Congestion Control (TCP Reno): Developed a congestion control algorithm based on TCP Reno, including slow-start, congestion avoidance, fast recovery, and timeout behavior for managing network congestion.
  - Implemented and Compared TCP CUBIC: Implemented the TCP CUBIC congestion control algorithm and compared its performance with TCP Reno through experiments focusing on efficiency and fairness.
 
- **Compiler, Parser, and Interpreter Development in OCaml (Prolog Queries)**
  - Defined regular expressions in OCamllex and Yacc to parse Prolog programs based on grammar rules.
  - Developed a Parser to transform the Prolog program input into Abstract Syntax Trees (ASTs).
  - Implemented an Interpreter in OCaml that traverses the ASTs to execute Prolog queries, providing query results.
 
- **EduQuest- Interactive game on child education in C++**
  - Developed a 2D desktop game aimed at raising awareness for child education in underprivileged areas. The game features two parts: a running game with obstacles and rewards, and a memory game to test intelligence.
  - Implemented customizable settings allowing players to change character appearance and toggle sound.
  - Designed an interactive home page displaying the player’s score and rewards. Included a donation link to an NGO at the end of each game, encouraging support for the cause.
  - Used SFML for graphics and audio in C++ to create an engaging, interactive user experience.
  - Focused on a user-friendly interface suitable for players of all ages and backgrounds. Platform: Desktop (2D visuals).
  
### 📫 For further details regarding any of the projects, please contact
- 💌 Email: [riti.iitd.cse@gmail.com](mailto:riti.iitd.cse@gmail.com)  
- 💼 LinkedIn: [Riti Verma](https://www.linkedin.com/in/ritiverma)  

