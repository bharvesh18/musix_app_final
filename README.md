# Music Player App

This music player allows user to play songs , forward them using control, play previous or next song, shuffle playlist and play the music on loop. Overall this music app provides all the basic functionalities of a web music player application.

## Features

  -**Play or Pause Song**
  -**Play Previous Song**
  -**Play Next Song**
  -**Shuffle Playlist**
  -**Play on Loop**

## Installation

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd <project-directory>
   ```

3. **Install Dependencies**

   Make sure you have [Node.js](https://nodejs.org/) installed. Then run:

   ```bash
   npm install
   ```

## Usage

1. **Start the Development Server**

   ```bash
   npm run dev
   ```

2. **Open in Browser**

   Open your browser and navigate to `http://localhost:5172` to see the app in action.
   
## Components

1. **Player.jsx** - have functional implementations like:
                1. handlePlay(),playPrevious(),playNext()- These functions handle play contollers of our music app.
                2. updateProgress(),handleProgress()- These functions enables our players to play the music and provides a control to play the music from various timings.
                3. playOnRepeat(),randomPlayList()- Names of these functions itself suggest that these adds the functionality of playing the music on repeat and shuffling the playlist.
2. **PlayList.jsx**:
                1. This UI component displays music name, its thumbnail, singer' name and other details.
                2. List of all songs in the playlist are rendered using this component.  
