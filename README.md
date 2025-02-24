# 🐍 AI Snake Game using Deep Q-Learning 🎮  

This project is an **AI-powered Snake Game** built using **Python, Pygame, and Reinforcement Learning**. Instead of a human playing the game, an AI agent learns to play automatically using **Deep Q-Learning**, a popular reinforcement learning algorithm.

## 🚀 Features  
- 🧠 **AI learns by playing** – No human control required.  
- 🎮 **Pygame-based Snake Game** – Classic snake mechanics with AI integration.  
- 🤖 **Neural Network for decision-making** – AI uses a deep learning model.  
- 🌈 **Training with Reinforcement Learning** – The agent improves over time.  
- 🏆 **Performance Tracking** – View AI progress and scores in real-time.  

---

## 📌 **How It Works?**  

### 🎯 **Concept of Reinforcement Learning**  
The AI **learns by playing** through trial and error. It follows these steps:  

1. **Observes the game state** – The snake's position, food location, obstacles.  
2. **Chooses an action** – Move **left, right, up, or down**.  
3. **Receives a reward** –  
   - ✅ **+10** for eating food.  
   - ❌ **-10** for hitting a wall or itself.  
   - 🔄 **Small penalty** for unnecessary moves to encourage efficiency.  
4. **Updates its neural network** – The AI learns from past experiences and improves.  
5. **Plays thousands of games** – The model keeps getting better at playing.  

---

## 🏰 **Installation & Setup**  

### 🛠 **Step 1: Clone the Repository**  
```sh
git clone https://github.com/Syam-1133/AI-Snake-Game-using-Deep-Q-Learning
```

### 🛋 **Step 2: Install Dependencies**  
Ensure you have **Python 3.8 or later** installed. Then install required libraries:  
```sh
pip install pygame torch numpy matplotlib
```

### 🚀 **Step 3: Run the AI Training**  
To start training the AI:  
```sh
python helper.py
```
The AI will **begin playing and improving automatically**.  

### 🎮 **Step 4: Run the Trained AI Model**  
Once trained, you can let the AI play using:  
```sh
python agent.py
```
Watch the AI **play and improve over time!** 🎉  

---

## 📁 **Project Structure**  

| File          | Description |
|--------------|------------|
| `game.py`    | Implements the **Snake Game** using Pygame. |
| `agent.py`   | Runs the AI agent and allows it to play. |
| `model.py`   | Defines the **Neural Network** used for decision-making. |
| `helper.py`   | Trains the AI using **Deep Q-Learning**. |
| `README.md`  | Documentation for the project. |

---

## 🏆 **AI Training Process**  

### 1️⃣ **Game Environment (game.py)**  
The game is built using **Pygame** with standard Snake rules:  
- The **snake moves** continuously.  
- Eating food **increases score & length**.  
- Hitting the wall or itself **ends the game**.  

### 2️⃣ **Neural Network (model.py)**  
- A **deep learning model (Deep Q-Network)** is used.  
- It learns **optimal moves** based on past experiences.  
- Uses **PyTorch** for training the model.  

### 3️⃣ **Training the AI (train.py)**  
The **Q-Learning algorithm** trains the AI:  
- AI starts by **moving randomly**.  
- Over time, it **learns which actions are better**.  
- Rewards and penalties help it **improve**.  

### 4️⃣ **Testing the AI (agent.py)**  
- The trained model is loaded.  
- AI **plays automatically** without human input.  
- Over time, it **gets better and survives longer**.  



## 🚀 **Future Improvements**  
🔹 Add **more advanced AI algorithms** (like DQN with Experience Replay).  
🔹 Improve **game graphics and animations**.  
🔹 Allow **human vs AI** gameplay.  
🔹 Optimize training **for faster learning**.  

---

## 👨‍💻 **Author**  
- **[Your Name]**  
- 📧 Email: your.email@example.com  
- 🌍 [GitHub Profile](https://github.com/Syam-1133)  

---

## 📜 **License**  
This project is licensed under the **MIT License** – free to use and modify!  


