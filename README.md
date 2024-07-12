
# Guitar-Ultimate-Hero

Guitar-Ultimate-Hero transforms your guitar practice by turning standard tablature playback on [Ultimate Guitar](https://tabs.ultimate-guitar.com/) into an interactive experience inspired by rhythm games like Rocksmith and Guitar Hero. This Chrome extension dynamically captures and displays notes, providing a fun and engaging interface for guitarists of all skill levels to improve their performance.

## Features
- **Interactive Gameplay**: Engage with guitar tabs in a game-like format that makes learning more fun and effective.
- **Real-Time Feedback**: Get immediate feedback on your guitar playing, helping you quickly correct mistakes and enhance your skills.
- **Customization**: Adjust difficulty settings and choose from various songs to personalize your practice sessions.
- **All Skill Levels**: Whether you are a beginner or an experienced guitarist, Guitar-Ultimate-Hero offers a valuable practice tool.

## Technology Stack
- **React 18**: For building a responsive and modern user interface.
- **Webpack 5**: Efficiently compiles and bundles the code, ensuring quick load times and a smooth user experience.
- **TypeScript**: Adds type safety and enhances the development experience with robust tooling.
- **Chrome Extension Manifest V3**: Utilizes the latest features available for Chrome extensions to ensure compatibility and performance.

## Getting Started
1. Clone this repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm start
   ```
4. Load the unpacked extension into Chrome:
   - Navigate to `chrome://extensions/`
   - Enable "Developer Mode"
   - Click "Load unpacked" and select the `build` directory.

## Important
This extension is specifically designed to work with the tablature interface on [Ultimate Guitar](https://tabs.ultimate-guitar.com/). It hooks into the existing web infrastructure to enhance the practice experience without altering the original content.

## Acknowledgements
Guitar-Ultimate-Hero is built upon the [Chrome Extension Boilerplate with React 18 and Webpack 5](https://github.com/lxieyang/chrome-extension-boilerplate-react) originally developed by lxieyang. This boilerplate provides a solid foundation for developing modern Chrome Extensions using the latest web technologies.

## Build and Deployment
Build a production-ready version of the extension:
```bash
npm run build
```
The resulting `build` folder contains all necessary files ready for deployment to the Chrome Web Store.

## Contribute
Contributions are welcome! Please feel free to submit pull requests, report bugs, or suggest features through the project's GitHub issues page.

## License
Guitar-Ultimate-Hero is open-sourced under the MIT license and is free for modification and distribution, respecting the original licensing terms of the utilized boilerplate.

Enjoy enhancing your guitar skills with Guitar-Ultimate-Hero and rock out to your favorite songs!
