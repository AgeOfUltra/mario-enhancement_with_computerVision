
<html>

  <head>
    
  </head>
  <body>
  <H1>Mario: Enhancement With ComputerVision</H1>
  <p>It's a final year project where we have developed a computer vision application to interact with mario or any game which support basic action on "AWSD" keys </p>
  <hr>
  
  <p>In this project we have developed  3 models </p>
  <ul>
    <li><strong>Model 1 : </strong>Action performing based on the color detection in the region of intrest</li>
     <li><strong>Model 2 : </strong>Action performing based on the Hand Gesturet</li>
     <li><strong>Model 3 : </strong>Action performing based on the both color detection and Hand Gesture(Hybrid Model)</li>
  </ul>
       <h1>Design Implementation of Super Mario Computer Vision Models</h1>
        <h2>Model 1: Color Detection</h2>
      <p>
          <strong>Description:</strong> This model uses color detection algorithms to recognize specific colors placed within defined regions of the game screen. Actions like moving right, left, or jumping are triggered based on the detected colors.
      </p>
      <h3>Implementation Steps:</h3>
      <ol>
          <li> Use OpenCV library to capture frames from the game screen.</li>
                   <li> Contour Area where color detection will be performed</li>
                   <li> Apply color threshold techniques to isolate target colors within the area.</li>
                  <li> Implement logic to map detected colors to corresponding game actions </li>
      </ol>
    <h3>How to use color detection model ?</h3>
    <ul>
      <li>First pick a solid colored matirial and run the program in the folder color.py and set the HSV values according to it  </li>
      <li>Now use those HSV values in the control.py at the line 27 and run the programm!</li>
      <li>As well as for the hybrid model use the HSV value.</li>
    </ul>
   <h2>Model 2: Hand Gesture Recognition</h2>
      <p>
          <strong>Description:</strong> This model interprets hand gestures captured by a camera to control Mario's movements in the game. Different gestures correspond to actions like moving and jumping.
      </p>
      <h3>Implementation Steps:</h3>
      <ol>
         <li> deep learning framework like TensorFlow to develop a gesture recognition model.</li>
                  <li>  Collect and preprocess a dataset of hand gesture images for training</li>
                 <li>   Train a convolutional neural network (CNN) model to recognize gesture </li>
                   <li>Implement gesture detection, from camera feed and mapping them with action.</li>
      </ol>
  
<h2>Model 3: Hybrid Model (Color + Gesture)</h2>
      <p>
          <strong>Description:</strong> This hybrid model combines the functionalities of color detection and hand gesture recognition to provide a more robust and versatile control mechanism for Super Mario gameplay.
      </p>
      <h3>Implementation Steps:</h3>
      <ol>
         <li>Design a decision-making algorithm to prioritize inputs </li>
              <li> Develop logic to dynamically switch between color-based and gesture-based </li>
               <li> Implement a fusion mechanism that integrates outputs from both </li>
         </ol>
  
  <hr>
  
  <h2>DataSet</h2>
    <p>Here are the images of gesture used in the models and to train them </p>
    ![Left](https://github.com/AgeOfUltra/mario-enhancement_with_computerVision/assets/98634633/b8eb722d-e3ef-4b49-951d-7eb42f60d320)
    <br/>
    ![Jump](https://github.com/AgeOfUltra/mario-enhancement_with_computerVision/assets/98634633/8c753063-9e4e-4ef6-89b4-49166718ea96)
    <br/>
    ![right](https://github.com/AgeOfUltra/mario-enhancement_with_computerVision/assets/98634633/e31c047c-4c64-4dea-b731-6978ac1491a0)
    <br/>
    ![fire](https://github.com/AgeOfUltra/mario-enhancement_with_computerVision/assets/98634633/913560e1-2641-4b45-9bad-5f3f17fb75bf)

  <hr>
  <p>We used the pre trained models from the website <a href="https://teachablemachine.withgoogle.com/train/image">techabalemachinewithgoogle</a></p>
  </body>
  <footer>Download the code! download the liberaries according to the requiremnt.txt file Run the code and Enjoy!</footer>
</html>
