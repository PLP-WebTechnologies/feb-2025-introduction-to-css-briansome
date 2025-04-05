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
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Styled Page</h1>
        <img src="placeholder-image.jpg" alt="A placeholder image" class="header-image">
    </header>

    <main>
        <section class="content">
            <h2 id="section-title">About This Page</h2>
            <p>This page demonstrates how to use external CSS to style HTML elements. We are using various selectors to apply different styles.</p>
            <div class="info-box">
                <p>Here is some additional information in a styled box.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Styled Page</p>
    </footer>
</body>
</html>
