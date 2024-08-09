**Songtext Analyser**

While listening to a foreign song, one might ask : "What are they singing". Let's find out.

The Songtext analyser is and end-to-end solution that allows you to enter a youtube URL of our favorite song, extract the song as an MP4, convert to MP3 and analyse the songtext using a large language model.

files in this repository:

**data folder**
This folder stores the imported MP4 files (youtube music video's)

**data_mp3 folder**
This folder stores the MP3 files, extracted from the MP4 files 

**data_import.ipyn**
This ipynb creates the mp4 files in the data folder by connecting to youtube

**data_to_mp3.ipyn**
Converts all mp4 files in the data folder to mp3 and stores them in the data_mp3 ilfder

**episodes.csv**
This file contains the urls of the youtube video's that you want to import

**main.ipyn**
The main.ipynb uses the MP3 files to extract the text and interpret it.

Note : the main.ipynb file requires an OPENAI API KEY. In this repository, it is assumed that the key is stored in the environment variables of the local machine.

