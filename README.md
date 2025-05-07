# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Assignment</title>

  <!-- Link to Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">

  <!-- Link to external CSS file -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header id="main-header">
    <h1>Welcome to My Styled Page</h1>
    <p class="subtitle">Learning CSS is fun and powerful!</p>
  </header>

  <section>
    <img src="https://via.placeholder.com/300" alt="Sample Image" class="profile-image">
    <p>This page demonstrates how to apply CSS using an external stylesheet. We're using different selectors, fonts, and spacing techniques.</p>
  </section>

</body>
</html>

<!--CSS FILE-->
/* Use a different font */
body {
  font-family: 'Roboto', sans-serif;
  background-color: #f5f7fa;
  margin: 0;
  padding: 20px;
}

/* ID Selector */
#main-header {
  background-color: #4a90e2;
  color: white;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
}

/* Class Selector */
.subtitle {
  font-size: 18px;
  margin-top: 5px;
  color: #dfe6f3;
}

/* Element Selector */
p {
  font-size: 16px;
  line-height: 1.6;
  margin-top: 20px;
  color: #333;
}

/* Image Styling */
.profile-image {
  width: 300px;
  border: 5px solid #4a90e2;
  border-radius: 10px;
  padding: 10px;
  margin-top: 20px;
}

