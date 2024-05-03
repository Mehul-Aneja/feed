<h1 align='center'>Feed Player - For Images, Video and Text</h1>

[![video-player](https://github.com/sahilatahar/Video-Player/assets/100127570/8315e5d3-9b16-4b37-a50c-141a96f2e72e)](https://video-player-sahilatahar.netlify.app/)

Welcome to our Feed-Player React Project! This project provides a modern and user-friendly interface for viewing a series of images and video pulled from RSS, JSON, CSV and YAML. The UI is built using Vite, ReactJS, HTML, CSS, and JavaScript. The Feed-Player is designed to be fully responsive and packed with a range of features to enhance your viewing experience.

## Feed Samples

View and [add your feeds](view)

TO DO: Update the code to pull from these.

[JSON for video, image and feed links](src/Data/data.js) - We will also load from CSV files
[Bluesky RSS Feeds](https://bsky.app/profile/todex.bsky.social/post/3kj2xcufu5q2q) - Add a sample Bluesky RSS link to our [feed view](view).
[Swiper Element](https://swiperjs.com/element) will be used for film-strip-style navigation.

**Also see:**  
[Swiper Element Setup](https://www.freecodecamp.org/news/how-to-set-up-swiper-element-in-a-react-application/)  
[Film-strip sample](https://www.sliderrevolution.com/templates/wordpress-media-gallery) - We'll avoid showing multiple heros at the same time  



## Features

&#9658; &nbsp; Play/Pause: Easily start and pause the playback with a single click.  
&#9632; &nbsp; Stop: Stop the feed playback and reset it to the beginning.  
🔊 &nbsp; Volume Control: Adjust the volume level to your preference by increasing or decreasing the volume.  
🔇 &nbsp; Mute: Quickly mute or unmute the feed's audio with the mute button.  
&#9970; &nbsp; Full-Screen: Enjoy your videos in full-screen mode for an immersive viewing experience.  
&#9202; &nbsp; Remaining Time: The feed player will display the remaining time of the current feed.  
&#9654; &nbsp;Navigation: Seamlessly navigate to the next or previous item in the playlist.  
&#128250; &nbsp; Play by URL: Paste a feed URL to play any valid feed format directly from the web. (Coming soon)

## New UI and Controls

The Feed-Player project boasts a brand-new user interface that is both visually appealing and intuitive to use. The controls have been thoughtfully designed to provide easy access to the various functionalities while keeping the user experience smooth and engaging.

## Live Preview

Check out the live preview of the Feed-Player project on Netlify: [Live Preview](https://video-player-sahilatahar.netlify.app/)

## Getting Started

To run the Feed-Player project locally, follow these steps:

1. Clone this repository to your local machine using:

   ```
   git clone https://github.com/modelearth/feed.git
   ```

2. Navigate to the project directory:

   ```
   cd feed
   ```

3. Install the required dependencies using your preferred package manager. For example, with yarn:

   ```
   yarn
   ```

4. Start the development server:

   ```
   yarn dev
   ```

5. Open your web browser and go to `http://localhost:5173` to access the Feed-Player application.

## Technologies Used

- ReactJS: Building the user interface and managing component-based architecture.
- Vite: Fast and lightweight frontend tooling for development.
- HTML: Structuring the content and layout of the video player.
- CSS and SCSS: Styling the UI components and ensuring responsiveness.
- JavaScript: Adding interactivity and logic to the video player functionality.

Vite is preferable to Create React App (CRA) because Vite does not rebuild the whole app whenever changes are made. It splits the app into two categories: dependencies and source code. Dependencies do not change often during the development process, so they are not rebuilt each time thanks to Vite.

## Contributions

Contributions to the Feed-Player React Project are welcome! If you have any improvements, bug fixes, or additional features in mind, feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](https://github.com/ModelEarth/feed/blob/main/LICENSE),  
which means you are free to use, modify, and distribute the code as you see fit.

---

We hope you enjoy using the Feed-Player!
If you have any questions or feedback, please reach out by posting a [discussion item](https://github.com/orgs/ModelEarthTeam/discussions).

Happy feed watching! 🎥🍿
