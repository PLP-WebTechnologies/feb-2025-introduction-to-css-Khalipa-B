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

index.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Web Dev Week 3 Assignment</title>
    <link rel="stylesheet" href="src/style.css" />
  </head>
  <body>
    <header id="main-header">
      <h1>Welcome to My Styled Page</h1>
    </header>

    <section>
      <p class="text-content">
        This is a simple webpage styled using CSS. CSS helps in improving
        readability and aesthetics by using different colors, fonts, margins,
        paddings, and borders.
      </p>

      <img
        src="https://cdn.mos.cms.futurecdn.net/Vp9WvV7YKdH4k8sKRePcE8-650-80.jpg.webp"
        alt="Coding Image"
        class="img-style"
      />

      <a href="https://en.wikipedia.org/wiki/CSS" class="button">Learn more</a>
    </section>
  </body>
</html>

style.css

body {
  font-family: "Arial", sans-serif;
  background-color: #f4f4f4;
  color: #333;
  margin: 0;
  padding: 0;
}

#main-header {
  background-color: #043e64;
  color: white;
  text-align: center;
  padding: 20px;
  border-bottom: 5px solid #2980b9;
}

.text-content {
  font-size: 18px;
  line-height: 1.6;
  margin: 20px;
  padding: 10px;
  border-left: 5px dotted #043e64;
}

.img-style {
  display: block;
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  margin: 20px auto;
  border: 3px solid #043e64;
}

.button {
  display: inline-block;
  background-color: #043e64;
  color: white;
  padding: 5px 5px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
  margin: 10px;
}

.button:hover {
  background-color: white;
  color: #043e64;
}
