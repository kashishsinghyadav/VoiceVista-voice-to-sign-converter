# Speech-to-Sign-language-Translator
**An application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.**
- Front-end using EasyGui.
- Speech as input through microphone using PyAudio. 
- Speech recognition using Google Speech API and Sphix(for offline use).
- Text Preprocessing using NLP.
- Dictionary based Machine Translation.

## To run the application.
1. Open the Downloads folder and then open the terminal.
2. From the terminal, run the *main* python file using the command **python main2.py**.
4. The application interface appears on the screen.
5. Hit the record button to start taking speech as input.
6. Any speech recorded is then processed and respective outputs are shown accordingly.
7. To exit the application using speech, say *goodbye*.


**Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically conveyed sound patterns, sign language uses body language and manual communication to fluidly convey the thoughts of a person. Due to considerable time required in learning the Sign Language,  it becomes difficult to communicate with these specially abled people, and thus creates a communication gap.**

## Objective
**This Audio to Sign Language converter aims at :**
- Providing information access and services to deaf people in Indian sign language.
- Developing a scalable project which can be extended to capture whole vocabulary of ISL through manual and non-manual signs

It can be developed as a desktop or mobile application to enable specially abled people to communicate easily and effectively with others

**Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically conveyed sound patterns, sign language uses body language and manual communication to fluidly convey the thoughts of a person. Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these specially abled people, creating a communication gap. Thus, we propose an application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.**

## Algorithm
Audio to Sign Language Translator
1. Start
2. Getting the Speech
   1. Listen for 1 second and calibrate the energy threshold for ambient noise
levels.
   2. Listen the Speech using Microphone.
Now the energy threshold is already set to a good value, and we can
reliably catch speech right away.
3. Recognise the Speech.
4. Convert Speech to Text.
   1. Make the Text to lowercase for further manipulation.
5. Detected Text
   1. If “goodbye” then exit.
   2.Else if Detected Text in predefined Dictionary Words. Display
respective GIFs of the Phrase.
   3. Else Count the Letters of the Word/Phrase.
      1. Display the Visual of the phrase with some delay of Actions.
   4. Continue all the steps from Step 3, and continue till the Speech Ends.
6. If Error in Step 2, That is if no Speech Detected then display error message
“Could not listen”.

**Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these specially abled people, creating a communication gap. Thus the Audio to Sign Language converter is important and significant because it helps in providing information access and services to deaf people in Indian sign language and develops a scalable project which can be extended to capture whole vocabulary of ISL through manual and non-manual signs. It also can be developed as a desktop or mobile application to enable specially abled people to communicate easily and effectively with others.**


## 𝐫𝐮𝐧 𝐜𝐨𝐦𝐦𝐚𝐧𝐝 𝐦𝐚𝐢𝐧.𝐩𝐲 𝐭𝐡𝐢𝐬 𝐬𝐡𝐨𝐮𝐥𝐝 𝐝𝐢𝐬𝐩𝐥𝐚𝐲  𝐚𝐧𝐝 𝐭𝐡𝐞𝐧 𝐜𝐥𝐢𝐜𝐤 '𝐤𝐮𝐜𝐡 𝐭𝐨 𝐛𝐨𝐥o' 𝐭𝐨 𝐬𝐩𝐞𝐚𝐤 

![Screenshot (105)](https://github.com/kashishsinghyadav/VoiceVista-voice-to-sign-converter/assets/117498422/b6a88f97-443f-4448-a65c-4251d4542067)


** 𝐬𝐩𝐞𝐚𝐤 𝐚𝐧𝐝 𝐭𝐡𝐞 𝐚𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐩𝐫𝐨𝐯𝐢𝐝𝐞 𝐲𝐨𝐮 𝐠𝐢𝐟 𝐨𝐫 𝐬𝐢𝐠𝐧 𝐥𝐚𝐧𝐠 𝐭𝐨𝐰𝐡𝐢𝐜𝐡 𝐣𝐮𝐬𝐭𝐢𝐟𝐲 𝐲𝐨𝐮𝐫 𝐰𝐨𝐫𝐝𝐬


![Screenshot (106)](https://github.com/kashishsinghyadav/VoiceVista-voice-to-sign-converter/assets/117498422/0c5d0de8-b11d-442a-87d5-548e895750a4)
