# NYC Evictions Sonification
### An adaptation of Matt Russo's Data Sonification Tutorial in Python

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
