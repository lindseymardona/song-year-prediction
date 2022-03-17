# Song Predictive Year

Contributors: lindseymardona, jbfranco21, ryansuwarno

## The Task
Our goal is to aid in exploratory analysis of the Million Songs Dataset through visualizations of the data.

## The Dataset
The Million Song Dataset (MSD) is a collection of 1,000,000 contemporary, popular music tracks with their associated audio features and metadata. The songs are mostly of western origina and release years range from 1922 to 2011, with a peak in songs from the 2000s. The dataset used is a subset of the Million Song dataset, with 10,000 tracks.

### Track Information:
Each track description includes the following:
  - **SongNumber** - Number associated with the order in which the song appears in the dataset
  - **SongID** - The Echo Nest song ID
  - **AlbumID** - The Echo Nest album ID
  - **AlbumName** - Name of the Album
  - **ArtistID** - The ID of the artist accorrding to playme.com
  - **ArtistName** - Artist Name
  - **Danceability** - Danceability measure of the song according to The Echo Nest
  - **Duration** - Duration of the song track
  - **KeySignature** - Estimation of the key of the song according to The Echo Nest
  - **Tempo** - Tempo in BPM according to The Echo Nest
  - **TimeSignature** - Time signature of song according to The Echo nest (beats per minute)
  - **Title** - Song Title
  - **Year** - Year when the song was released, according to musicbrainz.org
  - **SongHotness** - According to The Echo Nest, the hotness of the song when downloaded (scale of 0 to 1)

## Installations
....
"Instructions on how to install the package requirements. If you used the conda line above, your instruction should have the line conda create --name NEWENV --file requirements.txt."

## Scope and Limitations
While data cleaning, certain songs were removed dude to special characters within the album or track titles. 

....
Scope and limitations, including ethical implications, accessibility concerns, and ideas for potential extensions.

## Description of the demo file
"Detailed description of the demo file. This includes detailed instructions on how to run it, what output one should expect to see, and any explanations or interpretations of the result. There should be at least 2 figures embedded in this section. It can be screenshots of your game, or plots generated by your data visualization code. Make sure these figures have appropriate titles and captions, and are sufficiently explained in your text.
....
The csv. file used was a randomly chosen subset of the Million Song Dataset. The file included 10,000 tracks in total, but required data cleaning to remove unnecessary columns and tracks with missing data.
...

<img width="1125" alt="Screen Shot 2022-03-16 at 8 02 16 PM" src="https://user-images.githubusercontent.com/100387860/158729449-c68dfb91-77e4-4c85-9018-66fbb7a733ae.png">
<img width="1129" alt="Screen Shot 2022-03-16 at 8 02 27 PM" src="https://user-images.githubusercontent.com/100387860/158729519-79d994f1-5c54-46ff-a709-39b0ebd85919.png">
<img width="1124" alt="Screen Shot 2022-03-16 at 8 02 36 PM" src="https://user-images.githubusercontent.com/100387860/158729529-ea68791e-e194-4b62-82ff-11ffced79cde.png">
<img width="1129" alt="Screen Shot 2022-03-16 at 8 02 44 PM" src="https://user-images.githubusercontent.com/100387860/158729543-65b528b7-df0b-43b6-9c0b-6cf0b8f69a0e.png">
<img width="1109" alt="Screen Shot 2022-03-16 at 8 02 53 PM" src="https://user-images.githubusercontent.com/100387860/158729555-9b5e52cd-4a77-4def-8f15-f4b3f937d6a7.png">
<img width="1114" alt="Screen Shot 2022-03-16 at 8 03 02 PM" src="https://user-images.githubusercontent.com/100387860/158729561-7a0adacb-8e02-4a2c-a531-235cd0cef728.png">

## Licenses

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## References
Project utilizes the Million Song Dataset:
Thierry Bertin-Mahieux, Daniel P.W. Ellis, Brian Whitman, and Paul Lamere. 
The Million Song Dataset. In Proceedings of the 12th International Society
for Music Information Retrieval Conference (ISMIR 2011), 2011.
[link](http://millionsongdataset.com/)

UCI data description:
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science. [link](http://archive.ics.uci.edu/ml/citation_policy.html)

## Tutorials
https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge
Main project link which contains a dataset with 1,000,000 playlists created by Spotify users from January 2010 to October 2017
Contains playlist titles, track titles, last edit time, number of playlist edits, and other fields of metadata.
