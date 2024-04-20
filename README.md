<div align="center">

# Speech Emotion Recognition  

### What is Speech Emotion Recognition?  

</div>

**Definition** :

Speech emotion recognition (SER) is the field of technology focused on identifying the emotional state of a speaker from their voice. This goes beyond the words spoken and analyzes how they are spoken.


## How it Works


- **Speech Input:** Similar to standard speech recognition, the user's voice is recorded.
  
- **Pre-processing:** The audio is prepared by removing noise and potentially isolating specific speech segments.
  
- **Feature Extraction:** Crucial features related to emotions are extracted, including:
  - Prosodic features: Pitch, intonation, volume, speaking rate, pauses
  - Spectral Features: Spectrum of the voice, MFCCs (emphasizing qualities similar to human perception)
  - Voice Quality Features: Jitter, shimmer (small variations in voice quality)
    
- **Emotion Model:** A trained machine learning model (often using classification algorithms) takes these features and identifies the associated emotion.
  
- **Emotion Output:** The system outputs the detected emotion, typically with probability or confidence scores (e.g., angry, happy, sad, neutral, etc.).


## Applications of Speech Emotion Recognition


- **Mental Health:** Potential uses in diagnosing and monitoring mental health conditions, detecting stress or depression.
  
- **Customer Service:** Analyzing customer interactions in call centers to improve service and gauge satisfaction.
  
- **Human-Computer Interaction:** Creating more responsive and emotionally intelligent virtual assistants and robots.
  
- **Market Research:** Analyzing focus group responses or advertisement reception to understand emotional reactions.

- **Game Design:** Developing adaptive games that change based on a player's emotional state.


## Dataset Used


Ryerson Audio-Visual Database of Emotional Speech and Song (Ravdess)





## About Dataset

RAVDESS is one of the most common datasets used for this exercise by others. It's well-liked because of its quality of speakers, recordings, and it includes 24 actors of different genders. Additionally, it provides data in both speech and song formats, catering to a wide range of research projects. 

For convenience, here's the filename identifiers as per the official RAVDESS website:

- **Modality:** 
  - 01 = full-AV (audio-visual)
  - 02 = video-only
  - 03 = audio-only

- **Vocal channel:** 
  - 01 = speech
  - 02 = song

- **Emotion:** 
  - 01 = neutral
  - 02 = calm
  - 03 = happy
  - 04 = sad
  - 05 = angry
  - 06 = fearful
  - 07 = disgust
  - 08 = surprised

- **Emotional intensity:** 
  - 01 = normal
  - 02 = strong (Note: There is no strong intensity for the 'neutral' emotion)

- **Statement:** 
  - 01 = "Kids are talking by the door"
  - 02 = "Dogs are sitting by the door"

- **Repetition:** 
  - 01 = 1st repetition
  - 02 = 2nd repetition

- **Actor:** 
  - 01 to 24 (Odd numbered actors are male, even numbered actors are female)

So, here's an example of an audio filename: `02-01-06-01-02-01-12.mp4`

This means the metadata for the audio file is:
- Video-only (02)
- Speech (01)
- Fearful (06)
- Normal intensity (01)
- Statement "dogs" (02)
- 1st Repetition (01)
- 12th Actor (12) - Female (as the actor ID number is even)


## Overall Accuracy of this notebook


Accuracy: ⚽️......                                  62.407%

