
**Bash Scripting In Application**

#### Making A Guess-the-Song Script

In this exercise, we will be adding script code to build a simple game where the users guess the name of a song when its lyrics are outputted to the terminal. You may be wondering, how do we load in lyrics? We will take advantage of the script we ran in the introduction which fetches lyrics from the Internet. This lyrics script is a modified version of the lyrics script provided through Bash-Snippets.

We have provided a code skeleton for the script we are writing in the file named song_guesser.sh, which is already opened in the code editor. As a quick overview, the code contains:

- A while loop to continuously run the game until the user wishes to stop.
- A GenerateRandomArtistAndSong function that populates the variables artist_name and song_name with a random song name and its artist.
- Statements to print the lyrics into the terminal and prompt the user to make a guess.
- Statements to tell the user whether they guessed the right song name and if they wish to play again.

To fill in the script, we will pass the song name and the artist to the lyrics.sh script, retrieve the lyrics returned from that script, and output it in this song_guesser.sh script. Let’s begin!


