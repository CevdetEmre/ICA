# ICA
Independent Component Analysis
The "Cocktail Party Problem" is the typical problem used to describe ICA. Consider two people conversing at a cocktail party in its most basic form (like the red and blue speakers above). You have two microphones positioned near both partygoers for whatever reason (like the purple and pink microphones above). Based on the distance between the person and the microphone, both voices are heard at varying levels by both microphones. To put it another way, we record two files with audio from both partygoers combined together. So, how do we separate the two voices in each file so that we can have isolated recordings of each speaker?

This challenge is readily handled using Independent Component Analysis (ICA), which converts a set of vectors into a set of vectors that are maximally independent. Returning to our "Cocktail Party Problem," ICA will split the two mixed audio recordings (shown below as purple and pink waveforms) into two unmixed recordings of each speaker (represented by blue and red waveforms below). There are the same number of inputs and outputs, and because the outputs are mutually independent, there is no clear method to delete components, as there is in Principal Component Analysis (PCA).

![image](https://user-images.githubusercontent.com/86251983/164311847-e47f0f9d-8257-49c0-8206-61a0f0a80486.png)
