<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://ckl-website-static.s3.amazonaws.com/wp-content/uploads/2017/07/Banner_css-300x300.png.webp" alt="React logo" width="900" height="265">
  </a>
</p>

# Console Art X

This package allows you to write your name to the console once in your ReactJS application.

# Installation:

```
npm install console-art-x
```

# Usage:

```
import { writeName } from 'console-art-x';

const App = () => {
  const name = 'Bard';

  useEffect(() => {
    writeName(name);
  }, []);

  return (
    <div>
      <h1>{name}</h1>
    </div>
  );
};

export default App;
```

# Code Explanation:

- import { writeName } from 'console-art-x';: We import the writeName function from the package.
- const name = 'Bard';: We assign the name you want to print to a variable.
- useEffect(() => { writeName(name); }, []);: We use the useEffect hook to run the writeName function when the component first renders.

# Customization:

You can customize the appearance of the text using the <a href="https://patorjk.com/software/taag/"><strong> Patorjk</strong></a> website. This is an ASCII art generator that allows you to choose from a variety of fonts, colors, and sizes.

## To customize the code:

1. Go to the patorjk website.
2. Enter the text you want to print in the "Text" field.
3. Select the font, color, and size you want from the drop-down menus.
4. Click the "Generate" button.
5. Copy the generated text.
6. Paste the generated text into the writeName function call in your ReactJS code.

# Notes:

- This package is for development purposes only. It should not be used in production.

- The package works in the browser. It does not work in Node.js.

# Example:

You can continue the link to see the live example : <a href="https://github.com/MehmetBozkir/React_Weather_App_2.git"><strong> React Weather App </strong></a>

<img src="https://i.ibb.co/ssqtP5S/SH.png" alt="Example Photo" width="500" height="500">

# Troubleshooting:

If you encounter any problems, please open an issue on GitHub. <a href="https://github.com/MehmetBozkir"><strong> My Github Profile </strong></a>

# Thanks:

Thanks for using this package!
