# CSS 2D Transformations

## Overview

This project demonstrates all 9 types of 2D transformations in CSS. Each transformation is initially commented out in the code. To see how they work, simply uncomment each transformation one by one.

## Transformations Covered

1. **Translate**
2. **Rotate**
3. **Scale**
4. **Skew**
5. **Matrix**
6. **TranslateX**
7. **TranslateY**
8. **ScaleX**
9. **ScaleY**

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/css-2d-transformations.git

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS 2D Transformations</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="box">Transform Me!</div>
</body>
</html>

--css---
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.box {
  width: 100px;
  height: 100px;
  background-color: #007bff;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 16px;
  font-weight: bold;
  transition: transform 0.5s ease;
}

/* Uncomment each transformation one by one to see how they work */

/* 1. Translate */
/* .box:hover {
  transform: translate(50px, 50px);
} */

/* 2. Rotate */
/* .box:hover {
  transform: rotate(45deg);
} */

/* 3. Scale */
/* .box:hover {
  transform: scale(1.5);
} */

/* 4. Skew */
/* .box:hover {
  transform: skew(20deg, 20deg);
} */

/* 5. Matrix */
/* .box:hover {
  transform: matrix(1, 0.5, -0.5, 1, 0, 0);
} */

/* 6. TranslateX */
/* .box:hover {
  transform: translateX(50px);
} */

/* 7. TranslateY */
/* .box:hover {
  transform: translateY(50px);
} */

/* 8. ScaleX */
/* .box:hover {
  transform: scaleX(1.5);
} */

/* 9. ScaleY */
/* .box:hover {
  transform: scaleY(1.5);
} */
