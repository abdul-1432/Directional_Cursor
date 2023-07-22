# Directional Cursors

![1](https://github.com/abdul-1432/Directional_Cursor/assets/124916666/ed57c93c-35f1-4e83-bd99-a64e9716fd6d)


Directional Cursors is a fun and interactive project that enhances the user experience on your website by adding custom directional cursors. It replaces the standard cursor with a visually appealing and dynamic cursor that changes direction based on the user's mouse movement. This project is implemented using HTML, CSS, and Javascript, making it easy to integrate into any web application or website.

## Table of Contents

- [Demo](https://codepen.io/abdul-1432/pen/bGQjoOb)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Demo

Check out the live demo of Directional Cursors [here](https://codepen.io/abdul-1432/pen/bGQjoOb).


## Features

- Interactive and engaging directional cursors.
- Smooth and fluid animations.
- Easy integration into any website or web application.
- Customizable cursor styles and animations.
- Lightweight and optimized for performance.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/directional-cursors.git
```

2. Navigate to the project directory:

```bash
cd directional-cursors
```

3. Open the `index.html` file in your web browser to see the basic implementation.

## Usage

To integrate Directional Cursors into your website, follow these simple steps:

1. Copy the `CSS` and `js directories into your project's root directory.

2. Include the necessary CSS and JS files in your HTML file:

```HTML
<head>
  <!-- ... -->
  <link rel="stylesheet" href="css/directional-cursors.css">
</head>
<body>
  <!-- ... -->
  <script src="js/directional-cursors.js"></script>
</body>
```

3. Initialize the directional cursors in your JavaScript:

```HTML
<script>
  // Initialize directional cursors
  DirectionalCursors.init();
</script>
```

Now, when you run your website, you'll have the custom directional cursors active.

## Customization

Directional Cursors provides a set of options that you can customize to match your website's design and aesthetics. In the `js/directional-cursors.js` file, you'll find a section where you can modify the settings:

```javascript
const options = {
  cursory: "default",
  cursor size: 24,
  default cursor: true,
  color: "#FF5733",
  // Add more options here as needed
};
```

- `cursorType`: The type of cursor to display. You can choose between "default" or "custom". When set to "custom", make sure to define your custom cursor in the CSS file.

- `cursor size`: The size of the cursor in pixels.

- `default cursor`: Set this to `true` if you want to keep the default system cursor when hovering over non-interactive elements.

- `Color`: The color of the cursor. You can use any valid CSS color value.

Feel free to experiment with these options to achieve the desired visual effect.

## Contributing

Contributions are welcome! If you find any issues, have suggestions, or want to add new features, please feel free to open an issue or submit a pull request. Remember to follow the [code of conduct](CODE_OF_CONDUCT.md) when contributing.

## License

Copyright (c) 2023 by Mohammad Abdul Gafoor (https://codepen.io/abdul-1432/pen/bGQjoOb)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


---

Have fun adding Directional Cursors to your website! If you have any questions or need further assistance, don't hesitate to reach out. Happy coding!
