# NYC Evictions Sonification
## An adaptation of Matt Russo's Data Sonification Tutorial in Python

**References:**
* Matt Russo's [Tutorial](https://www.youtube.com/watch?v=DUdLRy8i9qI) on YouTube
* Original [Python script](https://github.com/SYSTEMSounds/sonification-tutorials/blob/main/data2midi-part1.py) on GitHub
* Data from [NYC OpenData](https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4/data_preview ), inspired by [Data Is Plural](https://www.data-is-plural.com/archive/2024-09-25-edition/)

**RJI Fellowship:**  
I'm building a data sonification toolkit for journalists, storytellers, and information designers! If you're interested in learning more, check out my [fellowship articles](https://rjionline.org/person/auralee-walmer/) (via the [Reynolds Journalism Institute](https://rjionline.org/)) or reach out at aurawalmer@gmail.com.

**Design Rationale:**
* **Mapping:** Lower, louder notes correspond to larger eviction rates, while higher, quieter notes correspond to smaller eviction rates. I made this choice because the deeper notes have a more resounding, impactful effect.
* **Musical key:** C Aeolian. Thematically, the topic of resident evictions is a somber one. I wanted the tone to reflect that.
* **Additional audio:** I captured audio from news segments on YouTube, as well as cricket sounds from freesound.org. The news segments are meant to help tell the story and inform the reader what historical/legislative events are happening over time.
* **Additional time marker:** The trianlge sound indicates the passing of each year (temporal context).

**Sonification Process:**
1. Convert data to MIDI in with Python script
2. Import MIDI file into audio editor (Logic Pro X in this case)
3. Customize and integrate additional audio layers  
(_I also got feedback from sonification friends via the [Decibels Community](https://decibels.community/)_.)
4. Export and share

**Materials in this Repository:**
1. Python Method (folder): `nyc-evictions-data2midi.py`
_Download contents of this folder to create this sonification with Python._
2. Jupyter Notebook Method (folder): `Jupyter Notebook Approach`  
_Download contents of this folder to create this sonification with Jupyter Notebook._
3. Data: `nyc-evictions.csv`
4. Script: `nyc-evictions-data2midi`
5. Supplemental function file: `functions.py`  
_Inlucde this in your working folder manually define the str2midi function from audiolazy._
6. MIDI output: `nyc-evictions.mid`

## Methods

### Method 1: Python  
Open your IDE of choice. Create a working folder and add the following downloaded files from this repo: nyc-evictions.csv, nyc-evictions-data2midi.py, functions.py.  

_Note about the audio_lazy package: there seem to be difficulties installing audio_lazy. The script `functions.py` includes the function definition needed from this package (a manual workaround, basically)._

### Method 2: Jupyter Notebok
Download files in the Jupyter Notebook Method folder, and upload it to a new space in [Jupyter Notebook](https://jupyter.org/try). 

### If you want to go straight to audio edting...
This repo also includes the MIDI file output from these methods. Feel free to download `nyc-evictions.mid` file direclty and drop it into your desired audio editing tool. 



