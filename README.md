# Floppify
An automator script that creates a floppy based record collection in Spotify

### HOW IT WORKS
Floppify is simply a script created with Automator. it watches the folder /Volumes of your Mac for a new drive called "FLOPPY" and if found, opens the spotify_link.txt file on it to copy the spotifyx URL into a variable which is than used to open the respective album/song/playlist.

### SETUP
simply download the file and double click. Your mac will ask you if you wish to install this folder watcher.

### USAGE
#### Spotify
1. open spotify
2. search for the album you want to use
3. rightclick and copy the Spotify URL from the "share" dialogue

#### spotify_link.txt
1. download the spotify_link.txt file
2. open it with any editor
3. paste the spotify URL into the file (only 1 per disk)
4. save the file to your hard drive

#### on the disk
1. connect the e.g. Floppy Disk drive to your Mac
2. insert a floppy disk (or USB drive)
3. copy your spotify_link.txt onto the floppy disk
4. rename the floppy disk to "FLOPPY"

=> if everything was correct, Spotify should now open and play the album :) ENJOY!
