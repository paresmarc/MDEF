---
hide:
    - toc
---

# Extended Intelligences
## AI and Machine Intelligence

### Colab

**Image Processing**

<img src="https://paresmarc.github.io/MDEF/images/printer1.jpeg" width="75%" height="75%"/>

Changing Confidence

<img src="https://paresmarc.github.io/MDEF/images/printer1_2.jpeg" width="75%" height="75%"/>

**Finding me inside the latent space**

Initial Image

<img src="https://paresmarc.github.io/MDEF/images/marcc.jpeg" width="75%" height="75%"/>

Image generated from the Latent Space

<img src="https://paresmarc.github.io/MDEF/images/marcX.png" width="75%" height="75%"/>

## Detector of Sexist behavior in Clubs

A device that recognizes sexist physical behavior and offensive speech to warn the environment of violence and abuse through changing music and light.

### Contextualization

In Spain, there are many cases of sexual aggression, generally from men towards women. It is a problem that needs to be solved because many women feel their freedom restricted and in many cases suffer physical or psychological aggressions.

There are many types of aggression, and therefore it is difficult to discriminate them by type, but with this project we seek to detect all types of sexist aggression, from a passing glance to a prick.

An INE report reveals that in 2021, 3196 sentences were imposed for crimes against sexual freedom and that 97.9% of the aggressors were male.

### Objectives

**Goals:**

The goal of this machine is to detect sexist behavior and remove aggressors from the club so that people can feel free and enjoy the full club experience. These detections are at different levels, such as gestures, glances, touching, expressions or syringe pricks.

On the other hand, this machine wants to show everyone whenever aggression is happening, so club users are aware of the high amount of sexism in our society. This system believes in the education model of awareness rather than punishment. Whenever aggression is detected, the song playing in the club changes, so everyone is warned and annoyed.

**Types of Smart Tasks:**

The tasks that the machine should be able to do to achieve perfect detection of sexist behaviors are, in the first hand, gesture analysis. This means scanning bodies and establishing relationships between them in order to determine when one of them is invading an individual's privacy. The next one is face recognition, which scans faces and facial expressions to analyze eyes and lips. Finally, microphones register sounds and conversations to let us know if someone is harassing another person.

**Dataset Format**
The technology used for the correct functioning of the machine is based on "machine learning". In machine learning, algorithms are trained to find patterns and correlations in large data sets and to make the best decisions and forecasts based on that analysis. Machine learning applications improve with use and become more accurate as they have access to more data.

The dataset programmed in the machine will allow the machine to be trained to correctly detect when there is sexist abuse in the clubs. The machine will learn based on questions like: "Is that a machism language?, Is that physical behavior sexist? , etc. If the machine detects something that is wrong, the next time the same situation occurs it  will know that it is not a sexist abuse and so on continuously with different situations that it captures.

### Colab and Dataset used

First of all, we were looking for datasets to recognize offensive language.
- Hate speech and offensive language dataset.
- Sexist workplace statements

Both are an excel spreadsheet where each column is an offensive phrase or word. It was collected from tweets via keywords and hashtags.

**Colab: Motion Detector**

The Colab tool has been used to execute Phyton codes to detect movements within clubs.
- Library name: Alphapose

<img src="https://paresmarc.github.io/MDEF/images/DataSet_SBD.jpg" width="100%" height="100%"/>

### Limitations & opportunities

**Some limitations of our machine:**

- Recognizing the sounds and conversations in detail is very complex and difficult, especially in crowded clubs because of music and the high volume of voices.

- In an unlit context, physical recognition could be hard and confusing. Also there should be a lot of cameras or sensors to detect every angle of the club, even if it's crowded and people cover themselves.
- Also, the large number of people in the clubs could make it difficult for the machine to control at the same time a lot of situations and possible sexist behaviors.
- People could feel that their privacy is invaded and that this system is trying to control them. Ethical issues associated with the machine. Should club users sign a contract for the cession of image privacy?

**Some opportunities to improve it:**

- Additional sensors in some body parts (wrists, ankles) of the users, as bracelets to help the cameras detect precise movements.
- The machine should incorporate several cameras in order to have different perspectives for image recognition.
- Night vision cameras or infrared sensors to detect better physical gestures.
- Make everyone sign a contract to agree on the terms.
- For ethical issues, only the users who want to be detected by the machine will be given the bracelets.
