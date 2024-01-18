# The Beatles – Discography Lyrics Analysis

1. **CORPUS**
    
    This corpus contains the lyrics of all 13 studio albums released by the Beatles, one of the most influential and popular rock bands in history of music. The albums span from 1963 to 1970, covering the different phases and styles of the Beatles’ style evolution. The corpus includes a total of 217 songs, with each song stored in a separate text file. 
    
2. **AUDIENCE AND USE**
    
    The target audience of this corpus are researchers, students, and enthusiasts who are interested in the Beatles’ lyrics and their linguistic and cultural aspects. The intended use of the corpus is to enable various natural language processing tasks, such as text generation, sentiment analysis, topic modeling, etc.
    
3. **TEXT SELECTION**
    
    The criteria for the corpus creation were the following:
    
    - The texts are the lyrics of the songs from the 13 studio albums released by the Beatles.
    - The texts are in English, the original language of the songs.
    - The texts are obtained from reliable and authentic sources, such as the Beatles’ [official website](https://www.thebeatles.com/) or [other](http://www.mldb.org/) verified lyrics websites.
    - The texts are formatted as plain text files, with each song stored in a separate file named after the song title.
4. **DATA COLLECTION**
    
    Songs lyrics were manually copied from [The Music Lyrics Database](http://www.mldb.org/) website.
    
5. **PRE-PROCESSING**
    
    The lyrics are stored in .txt files, with every file name corresponding to the track name. They are placed in the folders with the proper album name. 
    
6. **ANNOTATIONS**
    
    The spaCy library was utilized to enhance the original CSV by incorporating information such as Doc, Tokens, Lemmas, Part-Of-Speech, Named Entities, and their corresponding NE_Words for the songs. To streamline this process, the CSV was converted into a dataframe.
    
7. **DESCRIPTION OF COLUMNS IN ANNOTATED CSV**
    
    | Variable | Description |
    | --- | --- |
    | id | id |
    | album | the name of The Beatles album |
    | track | the name of the song |
    | lyrics | lyrics of the song |
    | cleaned_lyrics | lowercase lyrics without whitespace |
    | doc | spaCy processed text document |
    | lemmas | lemmatized text of the song lyrics |
    | pos | part of speech of the tokens found in the song lyrics |
    | named_entities | categories of Named Entities that are in the song lyrics |
    | ne_words | actual words of the Named Entities in the song lyrics |
   
9. **FORMAT**
    
    The individual song lyrics are in TXT, and the complete set is in CSV.

---
All lyrics are property and copyright of their owners. 
