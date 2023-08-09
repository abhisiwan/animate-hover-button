# Button Animation on Hover

A simple, modern, and elegant button animation effect upon hover. The button moves upwards with a smooth transition. Implemented using pure HTML and CSS with custom font integration from Google Fonts.

# Preview

A large button with the text "Button" and styled with a yellow background (#fde407), black border, and uses the "Poppins" font from Google Fonts. When hovered, the button animates upwards.

# Usage

1. Clone this repository to your local machine.
2. Open the index.html file in a browser to view the button.
3. To integrate it into your project, you can copy the HTML structure and link to the CSS, or you can adapt the styles to your existing structure.

# Code

 # HTML

<div class="container">
    <div class="button-container">
        <button>Button</button>
    </div>
</div>

# CSS

The main CSS features a button with a large font-size, generous padding, and a smooth upward transition on hover. Google Fonts ("Poppins") is used to style the button text.

body {
    background-color: aqua;
    font-family: "Poppins", sans-serif;
}
.container {
    min-height: 100vh;
    display: grid;
    place-items: center;
}
button {
    font-size: 64px;
    padding: 20px 40px;
    text-transform: uppercase;
    background-color: #fde407;
    border: 2px solid black;
    border-radius: 100px;
    transition: all 0.5s ease-in;
    cursor: pointer;
}
button:hover {
    transform: translateY(-15px);
}
.button-container {
    background-color: black;
    border-radius: 100px;
}
