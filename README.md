# Navig8
App developed to help the visually impaired navigate through natural calamities using peer to peer audio and video streaming by creating a mesh network that does not rely on wireless or cellular connectivity in the event of a failure.

![Image](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/000/836/783/datas/gallery.jpg)

## Inspiration
The moment we formed our team, we all knew we wanted to create a hack for social good which could even aid in a natural calamity. According to the reports of World Health Organization, there are 285 million people worldwide who are either blind or partially blind. Due to the relevance of this massive issue in our world today, we chose to target our technology towards people with visual impairments. After discussing several ideas, we settled on an application to ease communication and navigation during natural calamities for people with visual impairment.

## What it does
It is an Android application developed to help the visually impaired navigate through natural calamities using peer to peer audio and video streaming by creating a mesh network that does not rely on wireless or cellular connectivity in the event of a failure. In layman terms, it allows people to talk with and aid each other during a disastrous event in which the internet connection is down.

## How we built it
We decided to build an application on the Android operating system. Therefore, we used the official integrated development environment: Android Studio. By integrating Google's nearby API into our java files and using NFC and bluetooth resources, we were able to establish a peer to peer communication network between devices requiring no internet or cellular connectivity.

## Challenges we ran into
Our entire concept of communication without an internet or cellular network was a tremendous challenge. Specifically, the two greatest challenges were to ensure the seamless integration of audio and video between devices. Establishing a smooth connection for audio was difficult as it was being streamed live in real time and had to be transferred without the use of a network. Furthermore, transmitting a video posed to be even a greater challenge. Since we couldn’t transmit data of the video over the network either, we had to convert the video to bytes and then transmit to assure no transmission loss. However, we persevered through these challenges and, as a result, were able to create a peer to peer network solution.

## Accomplishments that we're proud of
We are all proud of having created a fully implemented application that works across the android platform. But we are even more proud of the various skills we gained in order to code a successful peer to peer mesh network through which we could transfer audio and video.

## What we learned
We learned how to utilize Android Studio to create peer to peer mesh networks between different physical devices. More importantly, we learned how to live stream real time audio and transmit video with no internet connectivity.

## What's next for Navig8.
We are very proud of all that we have accomplished so far. However, this is just the beginning. Next, we would like to implement location-based mapping. In order to accomplish this, we would create a floor plan of a certain building and use cameras such as Intel’s RealSense to guide visually impaired people to the nearest exit point in a given building.
