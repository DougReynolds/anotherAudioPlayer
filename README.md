#Another Audio Player  
**HTML5/jQuery Audio Playlist Player**

A bare bones audio player that allows the user to choose a song to play from a playlist.  

**Existing Website**  
Place the `audio`, `js`, and `styles` directories in your Website.  
Add the CSS to the HEAD of the Webpage you wish to add the player.

`<link rel="stylesheet" type="text/css" href="styles/styles.css">`  

Add the following HTML within the Webpage where you wish to display the player.  
```
<audio src="" controls id="audioPlayer">  
    Sorry, your browser does not support this audio player  
</audio>  
<ul id="playlist"> 
    <li class="current-song"><a href="audio/myAudio.mp3">My Description 1</a> </li>  
    <li><a href="audio/myAudio2.mp3">My Description 2</a> </li>  
    <li><a href="audio/myAudio3.mp3">My Description 3</a> </li>  
</ul>
```  
Add the following script imports to the bottom of your HTML page, just above closing body tag
```
<!-- jQuery -->
<script src="https://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>

<script type="text/javascript" src="js/player.js"></script>
```  
Add your .mp3 files to the `audio` directory.  
Modify the HTML list items `href` paths to your audio file names.  
Modify the `My Desicription` text as needed for each of your audio files.  
Add or remove the playist `li` List Items as needed for each of your Audio Files.  
