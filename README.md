## Pop Music Through the Ages: A CNN Model of Spectrograms

Using a database of mp3s from the Billboard Top 100 charts from 1955 to the present day, I created a model that classified pop songs by decade.  This model used a convolutional neural network trained on the spectrograms obtained from a 5 second clip from the middle of each song.  This model correctly identified the decade of 45% of the songs and correctly identified within one decade of 88% of the songs.  From this model, I was able to make many interesting observations about which decade’s music was the most distinctive, which songs were ahead of their time or reminiscent of earlier times, and which songs were most emblematic of their era.

![spectograms](github_pics/spectograms.jpg)

From this model, I've made some pretty cool insights about pop music through the ages.  Here are a few highlights:

* The seventies and the 2000s were the most distinctive music eras.  
* Some songs that were ahead of their time were:
    "Hey Jude" by the Beatles (from the 1960s and mistaken for the 1990s),
* Some songs that really exemplified their era were:
    "It's Too Late" by Carole King (from the 1970s),
    "So Emotional" by Whitney Houston (from the 1980s) 
* Some songs that really nailed the "retro" feel were:
    "Royals" by Lorde (from the 2010s and mistaken for the 1970s)
    "So Hard To Say Goodbye" by Boyz 2 Men (from the 1990s and mistaken for the 1960s)
    
See PopMusicCNN.ipynb for details of implementation.
