# Tear-animation
A tearing animation project
<!DOCTYPE html>
<html>
<head>
  <script src="https:                                                                   
  <style>
               
      width: 300px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <img id="tear-img" src="your-image.jpg" alt="Tear me!">
  <script>
    document.getElementById('tear-img').addEventListener('click', () => {
      gsap.to("#tear-img", {
        scale: 1.2,
        opacity: 0,
        duration: 1,
        ease: "power1.out",
        onComplete: () => {
          // Add particle or tear effect here (maybe using SVG)
          alert("Torn apart!");
        }
      });
    });
  </script>
</body>
</html>
