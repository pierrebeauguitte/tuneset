This repository contains annotations of Irish Traditional Dance Music recordings. The dataset is presented in a conference paper, to be published at ISMIR 2016: http://wp.nyu.edu/ismir2016/

Each line of the csv file is to be read as `onset, duration, MIDInote`.

Annotations have been made with the software Tony: https://code.soundsoftware.ac.uk/projects/tony

They can be imported easily with the software Sonic Visualiser: http://www.sonicvisualiser.org/

## List of tunes

| Name  | Type | Key | Source |
| ------------- | ------------- | -------------|  ------------- |
| Ballydesmond Polka No 1 | polka | D | Grey Larsen
| Ballydesmond Polka No 3 | polka | G | Comhaltas
| Brosna Slide | slide | G | Comhaltas
| Cork Hornpipe | hornpipe | D | Comhaltas
| Cronins Hornpipe | hornpipe | G | Grey Larsen
| Din Tarrants | polka | Am | Grey Larsen
| Down The Broom | reel | Am | Grey Larsen
| From Galway To Dublin | hornpipe | Em | Grey Larsen
| Get Up Old Woman | slide | Em | Grey Larsen
| Haunted House | jig | G | Comhaltas
| Humours Of Glendart | jig | D | Comhaltas
| Jackie Colemans | reel | D | Comhaltas
| Jack Regans | slide | Bm | Grey Larsen
| Jacksons | reel | Em | Bryan Duggan
| Jim Morrisons | jig | Em | Comhaltas
| Joe Cooleys | reel | Em | Comhaltas
| John Joe Lynch | jig | Am | Grey Larsen
| Lilting Banshee | jig | Am | Comhaltas
| Maids Of Mount Cisco | reel | Am | Comhaltas
| Morning Star | reel | Bm | Grey Larsen
| Munster Bacon | jig | D | Grey Larsen
| Music In The Glen | reel | G | Grey Larsen
| Out On The Ocean | jig | G | Comhaltas
| Over The Moor To Maggie | reel | G | Comhaltas
| Return From Fingal | other | Em | Grey Larsen
| Skylark | reel | G | Comhaltas
| The Humours Of Ballyconnell | jig | D | Bryan Duggan
| The Munster Bank | polka | G | Grey Larsen
| The Orphan | jig | Em | Grey Larsen
| Tuamgraney Castle | hornpipe | Am | Grey Larsen

## Source

Recordings come from three different sources, as indicated in the table above:

* session recordings accompanying the Foinn Seisiún books published by Comhaltas Ceoltóirí Éireann, available with Creative Common licence
* Grey Larsen's *MP3s for 300 Gems of Irish Music for All Instruments*, commercially available
* personal recordings of Bryan Duggan

## Obtaining the audio files

Grey Larsen's recordings can be purchased at http://greylarsen.com/store/catalog/product_info.php?cPath=25_44_65&products_id=111

The other recordings annotated in this dataset can be fetched by running the script `sh get_audio.sh`. The mp3 files will be downloaded in the `audio` directory.
