<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Imitation Assignment</title>
  <style>
    /* Image 1 */
    #image1 {
      filter: sepia(1);
      border-radius: 50%;
      border: 2px solid black;
      width: 30%
    }
    #image2 {
      filter: grayscale(1);
      border: 30px solid transparent;
      border-image-source: url('tic-tac-toe.png'); 
      border-image:url('tic-tac-toe.png') 50 round;
      width: 25%
    }
   #image3 {
      display: none; /* Hide Image 3, as it's used as a border */
    }
    #image4 {
     filter: hue-rotate(90deg) drop-shadow(10px -2px 3px #000000);
     width: 30%
   } 
    #image5 {
      background: linear-gradient(to bottom right, rgba(0, 0, 255, 0.5), rgba(255, 255, 255, 0.5)); 
      box-shadow: 0 7px 15px rgba(0, 0, 0, 0.5);
      width: 50%
    }
    
    #image6 {
      filter: invert(1);
      opacity: 0.7;
      border-radius: 100px 0 / 100px 0;
    }
    #image7 {position: absolute;}
    #image7 img {
     filter: blur(5px);
     width: 100%;
    }
    #presentingText {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      font-size: 52px;
      text-shadow: 0 2px 4px rgba(0, 0, 0, 2.5);
      z-index: 1;
    }
  </style>
</head>
<body>
  <p>Penguins</p>
  <p><img id="image1" src="penguins.jpg" alt="Image 1">
  </p>
  <p>Football Field with Tic-Tak-Toe Border</p>
  <p><img id="image2" src="football_field.jpg" alt="Image 2">
  </p>
  <p>Dinosaur</p>  
  <p><img id="image4" src="dinosaur.png" alt="Image 4">
  </p>
  <p>Seagull</p>  
  <p> <div id="image5">
      <img src="seagull.png" alt="Image 5">
      </div> 
  </p>
  <p> Butterfly</p> 
  <p><img id="image6" src="butterfly.jpg" alt="Image 6">
  </p>
  <p>Theater Stage</p> 
  <p><div id="image7">
     <img src="theater_stage.jpg" alt="Image 7">
     <div id="presentingText"> Presenting </div>
     </div>
  </p>
</body>
</html>
