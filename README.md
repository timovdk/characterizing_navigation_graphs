# characterizing_navigation_graphs

## Installation instructions
1. Clone this repo so that you have the folder `..\characterizing_navigation_graphs` on your machine.
2. The contents of [this repo](https://github.com/Archer-Tatsu/head-tracking) should be downloaded (as a .zip file) and extracted to the `..\characterizing_navigation_graphs\data\head_tracking_data` folder of the repo you just cloned.
    
        Correct: `..\head_tracking_data\Subject_...`
        
3. The contents of [this Dropbox](https://www.dropbox.com/sh/bs1pe50185ywhti/AAAL03q48Rg2Tcwpxc5MUNX6a?dl=0) folder should be downloaded and the video files should be placed in the  `..\characterizing_navigation_graphs\data\video_files` folder of our repo
    
    a. A thing to note: Don’t use the category folders (action sports, computer animations, movie, ...), just place the video files directly in the “..\characterizing_navigation_graphs\data\video_files” folder
        
        Correct: “..\video_files\Help.mp4”
        
    b. Another thing to note: For generate_pickle.ipynb to work you need all videos from Dropbox in the “..\characterizing_navigation_graphs\data\video_files” folder (as we index the videos, so with less videos the indices don't match up).
