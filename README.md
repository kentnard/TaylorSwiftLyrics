# TaylorSwiftLyrics
This repository is targeted to get all the lyrics from all the songs from Taylor Swift.  With the help of Genius API, it is possible to get the lyrics as well as additional information to the songs.

The data are fetched from only official studio albums ("Taylor Swift" to "THE TORTURED POETS DEPARTMENT : THE ANTHOLOGY"). I would like to update this repository every time she releases a new album. If you notice any defects in the code, or you have any new suggestion on which data should be added, please don't hesitate to contact. :) 

## If only need the raw data
There is a folder for each album. Inside, each song has its own .txt files which contains the raw lyrics of the song. Additionally, there are two excel files, which present the data in a tabular format. 
The file that ends with "full_album_info" contains additional information to the song, such as : 
1.  Track length
2.  Release Date
3.  Writer(s)
4.  Producer(s)
5.  Background vocal(s)
   
Meanwhile, the file that ends with "expanded_full_album_info" separates the lyrics per line, so that each line is represented in a single row.

## If you need the code part
You can open the file "All Taylor Swift Lyrics.ipynb" to see the magic behind it. If you need more information to the song, you could gladly download the source code and modify according to your needs. Make sure you have created an account in the Genius API and replace the variable "client_access_token" with *YOUR* access token. Please pay attention to the comments in the code, because the process is very delicate with Request and might lead to errors.


## Additional Note
While examining the data, I realized that there are some mistakes regarding the writing credits, in particular, with the songs "Bigger Than The Whole Sky" and "imgonnagetyouback". The former is credited with Taylor Swift and Jack Antonoff, but it is self-written by Taylor Swift; meanwhile the latter is credited as self-written, but it is written by Taylor Swift and Jack Antonoff. This is faulty from Genius' site. I have checked both Wikipedia and Spotify pages, and the data from Genius contradict them.
