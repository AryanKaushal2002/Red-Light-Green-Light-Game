# Red Light- Green Light Game
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


**Everyone knows this doll, right?**

![image](https://user-images.githubusercontent.com/92170372/232311919-2ea41bed-f557-4a29-bf3f-4ad492f37ecc.png)


*shivers* 

Here is the game Red Light - Green Light using Python where the user has to reach their respective device and press the key 'w' before the creepy doll can see them.

![image](https://user-images.githubusercontent.com/92170372/232312186-cec76e08-a57a-4645-9baa-612f79247f75.png)

If the light is red and you move, * *shoot* * immediate death.

The game takes input through your webcam or external camera device to locate the player and check if they have moved or not when the light is red. Movement during green light is allowed but the game ends if the doll detects the player moving or making sudden body movements when the light is red. 

**Note** : If your laptop/PC doesn't have an in-built webcam, certain changes need to be done in the code.
The code at line 28 in `game.py` will have to be changed from 

    cap = cv2.VideoCapture(0)

to 

    cap = cv2.VideoCapture(n) 


Here, n represents any number that your camera might represent in your system. It can be 1,2,3... or more depending on your system. So check out all the numbers in case it doesn't work.
This will hopefully allow the external camera to work.

## Getting Started
To play the Red Light - Green Light game, follow these steps:

1. Clone the repository:
    ```
    git clone https://github.com/your-username/Creepy-Doll-Game.git
    ```

2. Navigate to the project directory:
    ```
    cd Creepy-Doll-Game
    ```

3. Run the game:
    ```
    python game.py
    ```

4. Follow the on-screen instructions and enjoy the game!

## Requirements
- Python (version 3.6 or higher)
- OpenCV (version 3.4 or higher)
- Webcam or external camera device

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


