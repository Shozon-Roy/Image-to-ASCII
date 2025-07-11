# Image-to-ASCII

This application is an ASCII Art Converter that allows users to transform images into ASCII art representations. Users can upload images either by dragging and dropping them into the application or by using a file input. The app supports various character sets for ASCII art, including standard, detailed, block characters, and minimal options. 

To use the app, users can adjust the resolution of the ASCII art using a slider, toggle options for color inversion and grayscale mode, and select their preferred character set from a dropdown menu. Once an image is loaded, the app automatically converts it into ASCII art based on the selected settings. The resulting ASCII art is displayed in a preview area, where users can also see colored ASCII art if the grayscale option is disabled.

## Key features of the app include:
- Image upload via drag-and-drop or file selection.
- Adjustable resolution for ASCII art output.
- Multiple character set options for different styles of ASCII art.
- Options to invert colors and switch to grayscale mode.
- Copy to clipboard functionality for easy sharing of the generated ASCII art.
- Download option to save the ASCII art as a text file.

The application is built using React and TypeScript, leveraging hooks for state management and effects. It utilizes a canvas element for image processing and rendering, and it incorporates UI components for sliders, buttons, and select menus. The app is designed to be responsive, adapting its layout for both desktop and mobile users.
