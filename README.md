## Description of the Project:
We implement an advance Quantum Key Distribution Protocol : BB22 Protocol.
In this protocol, 3 parties sender(Alice), Reciever(Bob) and a computer(Quantum Computer) take part. This protocol can detect the presence of an eavesdropper in the quantum channel. 
Working:
    1. Alice prepares a state |+> and sends it to bob.
    2. Bob choses a random number either 1 or 0.
    3. 
        1. If bob picks the random number 0, then he makes the measurement in hadamard basis. basis.
       2.  If  he picks 1, then he will make the measurement in computational basis.
    4. Bob sends his measurement basis for each state to Alice.
    5. Alice correlates the bob’s measurement to determine the presense of eavesdropper, if the correlation value id other than zero than an eavesdropper is detected in the qauntum channel.
    6. If the correlation value is zero then channel is safe and Alice sends the key.


Instructions for running the project

We have created a GUI to perform this entire operation, The first Gui windows gives us the choice of playing the role of either sender or reciever.

<img src="https://github.com/alihakimtaskiran/2022_qutech_challenge/blob/main/Screenshots/Screenshot%20from%202022-01-30%2017-04-26.png">

The choice of sender allows us to put the number of bit in the key, the key and the message we want to deliver. The transmit button has the action of encrypting the message and putting it on a cloud. 

<img src="https://github.com/alihakimtaskiran/2022_qutech_challenge/raw/main/Screenshots/Screenshot%20from%202022-01-30%2017-10-48.png">

The reciever window will perform the Measure and the action of button is to perform measurement and the third party computer checks if the quantum channel is compromised or not, if it is not then the key is decrypted as

<img src="https://github.com/alihakimtaskiran/2022_qutech_challenge/raw/main/Screenshots/Screenshot%20from%202022-01-30%2017-09-56.png">

Link to presentation  :[https://github.com/alihakimtaskiran/2022_qutech_challenge/blob/main/Presentation.pptx](___)


Link to screenshots of results : [https://github.com/alihakimtaskiran/2022_qutech_challenge/tree/main/Screenshots](___)

Personal Experiences :

Ali Hakim : 
Having attended the hackathon, I have pushed myself hard work. Then I realized that there is no capacity of doing something. As I push it, it is enhanced itself. After learning that, I will learn more, produce more.

Raghav : 
It all started one year ago with qubit by qubit  course , i changed my pathways to Quantum Community . 
Last year when i got to know about MIT iQuHack , i was late . But this time , i made it to the hackathon.
I have not experienced hackathon like this ever , specially the gathertown event . I never thought that
i could directly  communicate with Quantum experts face to face.
Thank you iQuHack , quack! quack! </br> <b>-Raghav</b>

Haemanth : 
My personal experience: It was really fun working with people from different backgrounds and places but with similar interests. A very good learning experience.

Amithabh Kumar:
This was the first hackathon of my Life and I really enjoyed this  period of time.This hackathon created my interest in the world of Quantum Computing.The iQuHACK provided me the platform to meet with those enormous brains across the globe.In hackathon we are building the most advanced QKD(Quantum key Distribution)  that is amazing project and solve real life Quantum problem.I learn really from that and understand team work with computing and communication skill. I find this hackathon very intresting and also try to be part of other hackathons like that to rigorously learn a new thing.

Aman Gupta:
Hackathons have always been one of my favourite events to be a part of. In this hackathon I got to learn a lot and had a lively and exhilarating feeling throughout.
