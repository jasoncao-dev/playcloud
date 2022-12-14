# Project playcloud

Develop an elegant React.js Music Application.

# Technologies
1. **React.js** (Next.js)
2. **APIs**:
- Use _Shazam API_ to gather music data
- Use _Shazam Core API_ to gather artist details and recommended tracks
- Use _IP Geolocation API_ to get the user’s location
3. **Libraries**:
- TailwindCSS for UI
- _Redux Toolkit_ to keep the API calls organized

# Functionalities
1. **Music Playe**r - Users can click on any song, and a music player will appear. The player must include basic controls such as previous song, next song, and pause/play buttons. Additional details such as the song’s name, author, volume, repeat, and duration controls are a plus.
2. **Homepage** - Users can choose a genre and get top songs for that genre
3. **Explore** - Users can select a country and get top songs for that country
4. **Music for Specific Country** - Show the top songs for the user’s country
5. **Artists Page** - Users can see a list of the most famous artists
6. **Artist Details Page** - Users can see additional information about the artist and all of their most popular songs.
7. **Song Details Page** - Users can see additional information about the song, such as the song’s music video and lyrics and a list of similar songs.

## System Requirements

To get started with development, you need to install few tools

1. git 
   
   `git` version 2.13.1 or higher. Download [git](https://git-scm.com/downloads) if you don't have it already.

   To check your version of git, run:

   ```shell
    git --version
   ```

2. node 
   
   `node` version 16.15.1 or higher. Download [node](https://nodejs.org/en/download/) if you don't have it already.

   To check your version of node, run:

   ```shell
    node --version
   ```

3. npm
  
   `npm` version 5.6.1 or higher. You will have it after you install node.

   To check your version of npm, run:

   ```shell
    npm --version
   ```

## Setup

To set up a development environment, please follow these steps:

1. Install the dependencies
   
    ```shell
     npm install
    ```

    If you get an error, please check the console for more information.

    If you don't get an error, you are ready to start development.

2. Run the app
   
    ```shell
    npm run dev
    ```

    Project will be running in the browser.

    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
