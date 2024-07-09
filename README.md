# Customizable Hand Gesture Controller for Gamers
This project implements a customizable hand gesture controller for gamers using computer vision and machine learning. The system detects hand gestures in real-time video and maps them to various game controller inputs, providing a unique and immersive gaming experience.<br />

![Alt text](https://i.ibb.co/8dpfTvv/Picture2.png)

# Key Features
» Real-time Hand Gesture Recognition: The system utilizes advanced computer vision algorithms to accurately detect and track hand movements in the video feed.<br />
» Gesture-to-Input Mapping: Detected hand gestures are dynamically mapped to corresponding game controls, such as movement, actions, or menu navigation.<br />
» Customizable Gestures: Users have the flexibility to define and associate their preferred hand gestures with specific in-game actions, allowing for a personalized control scheme.<br />

# Cloning the project 
To clone the Customizable Hand Gesture Controller for Gamers project, follow these steps:<br />
1- Choose your IDE: You can use an Integrated Development Environment (IDE) like PyCharm or Visual Studio Code to clone the project.<br />
2- Open the Terminal: Once you have your IDE open, locate the terminal or command prompt within your IDE. The location of the terminal may vary depending on your IDE, but it is typically accessible through a menu or shortcut.<br />
3- Navigate to the Desired Directory: In the terminal, navigate to the directory where you want to clone the project. You can use the cd (change directory) command to navigate to the desired location on your local machine.<br />
4- Clone the Repository: In the terminal, type the following command to clone the repository:<br />
```ruby
git clone https://github.com/hdaw1905/Customizable_Hand_Gesture_Controller_for_Gamers.git   
```
# Requirements
In the terminal, navigate to the directory where you have clonned the project, and type the following commands:<br />
1- mediapipe 0.8.1 <br />
```ruby
pip install mediapipe
```
2- OpenCV 3.4.2 or Later <br />
```ruby
pip install opencv-python
```
3- Tensorflow 2.3.0 or Later<br />
```ruby
pip install tensorflow
```
4- scikit-learn 0.23.2 or Later (Only if you want to display the confusion matrix)<br />
```ruby
pip install scikit-learn
```
5- matplotlib 3.3.2 or Later (Only if you want to display the confusion matrix)<br />
```ruby
pip install matplotlib
```
6- keras<br />
```ruby
pip install tf-keras
```
7- Seaborn<br />
```ruby
pip install seaborn
```

# How To Run 
1- Navigate to the project directory:<br />
```ruby
cd Customizable_Hand_Gesture_Controller_for_Gamers
```
Then <br />
```ruby
cd hand-gesture-recognition-mediapipe
```
2- Run the app.py file:<br />
```ruby
python app.py
```
This will start the hand gesture recognition and mapping to the assigned keyboard keys.<br />

3- Open an online game in your web browser:<br />
Navigate to any online game website that you can play using the WASD keys for movement.<br />

4- Use the hand gestures to control the game:<br />
Perform the following hand gestures while playing the game:<br />

![Alt text](https://i.ibb.co/ByX1NzM/Picture1.png)<br />
'W' key presses (forward)<br />
'S' key presses (backward)<br />
'A' key presses (left)<br />
'D' key presses (right)<br />

The hand gestures will be detected in real-time, and the corresponding keyboard inputs will be sent to the game, allowing you to control the game using your hand movements.

# How to add cutsom hand gestures for specific controller
Soon .................

# To Do List
```[tasklist]
### My tasks
- [ ] https://github.com/octo-org/octo-repo/issues/45
- [ ] Draft task
```
# References 
Takahashi, S. (2020). hand-gesture-recognition-using-mediapipe [Computer software]. <br />
https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe<br />
https://github.com/google-ai-edge/mediapipe

