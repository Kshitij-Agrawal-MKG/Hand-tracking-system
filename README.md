# Hand Gesture Recognition with OpenCV and MediaPipe

## Project Overview

This Python script leverages the capabilities of OpenCV and MediaPipe to enable real-time hand gesture recognition using a webcam. The script captures video input from the default camera, processes the frames to detect and track hand landmarks utilizing the MediaPipe Hands module, and then overlays the detected landmarks onto the live feed. Each detected hand is annotated with its landmarks, with a distinctive filled circle indicating the first landmark (index 0). Additionally, the script calculates and displays the frame rate in the corner, providing insights into the processing speed. This project demonstrates the fusion of computer vision libraries to create an interactive experience, offering potential applications in fields such as virtual reality, gaming, and accessibility interfaces.

## Technology Stack

- OpenCV
- MediaPipe

## Getting Started

Follow these instructions to set up the project locally:

### Option 1: Clone from GitHub

1. *Clone the Repository*
   - Open your terminal or command prompt.
   - Navigate to your desired directory.



2. *Create a Virtual Environment* (Optional but recommended)
   - It's advisable to create a virtual environment to manage project dependencies. Execute the following command:

bash
conda create -p <Environment_Name> python==<python version> -y


3. *Activate the Virtual Environment* (Optional)
   - Activate the virtual environment based on your operating system:

bash
conda activate <Environment_Name>


4. *Install Dependencies*
   - Navigate to the project directory:

bash
cd Hand-Gesture-Recognition


   - Install project dependencies:

bash
pip install -r requirements.txt


5. *Run the Project*
   - Start the project by executing the following command:

bash
python app.py


6. *Access the Project*
   - Open a web browser or appropriate client to access the project.

## Contribution Guidelines

Contributions are welcome and greatly appreciated. To contribute to the project, follow these steps:

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

## License

Distributed under the MIT License. See LICENSE.txt for more details.

## Acknowledgements

We extend our sincere gratitude to all individuals and organizations who have contributed to the development and success of this project. Your support, whether through contributions, inspiration, or encouragement, has been invaluable. Thank you for being a part of our journey.