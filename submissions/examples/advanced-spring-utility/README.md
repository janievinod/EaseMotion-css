# Advanced Spring Utility

This component provides advanced physics-based spring animations for the EaseMotion-css library.

## ?? How to Use
Apply the spring utility classes to your target HTML elements:

\\\html
<div class="test-box ease-spring-bounce">
  Interactive Element
</div>
\\\
"@
Set-Content index.html @"
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EaseMotion-css Test Area</title>
  <link rel="stylesheet" href="../../../core/easemotion.css">
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f0f4f8;
      font-family: sans-serif;
      margin: 0;
    }
    .test-box {
      width: 150px;
      height: 150px;
      background-color: #0070f3;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      border-radius: 12px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.1);
      cursor: pointer;
    }
  </style>
</head>
<body>

  <div class="test-box ease-spring-bounce">
    Test Element
  </div>

</body>
</html>
