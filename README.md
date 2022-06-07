# sort_my_music

I hope to build a system where I can input music boaught by beatport read meta data create table with track title, album record label, artist, key BPM
the intitial step would be to sort and place music in files based on the meta data

I then want to go a step further and use a classification algorithm to try to sort the music into "vibe" understandble music feel is incredibly subjective
so the classification algorithm will be trained on my personal interpretations of the music, I am using this project as an oppurtunity to go deeper with my understanding of data 
science, by applying it in a field I love. the primary clasification will also save me a lot of time of sorting whenever I buy music from beatport so that means more time playing 

## Functions included

### Gather meta data 
This is the first step, I'll take the meta data of the music (bpm, key, artist, album, record lable) and create a panda data frame this is the data that will be used 
in the further classification steps 
