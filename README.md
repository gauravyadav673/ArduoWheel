Created by Team HORCRUX

## AutoRCCar
### Dependencies
* Raspberry Pi: 
  - Picamera
* Computer:
  - Numpy
  - OpenCV
  - Pygame
  - PiSerial
interface
- computer/
  -	cascade_xml/ 
    - trained cascade classifiers xml files
  -	chess_board/ 
    - images for calibration, captured by pi camera 
  -	training_data/ 
    - training image data for neural network in npz format
  -	testing_data/ 
    - testing image data for neural network in npz format
  -	training_images/ 
    - saved video frames during image training data collection stage (optional)
  -	mlp_xml/ 
    - trained neural network parameters in a xml file
