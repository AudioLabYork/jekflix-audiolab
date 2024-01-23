---
# date: 2010-09-10 12:26:40
layout: post
title: Maida Vale Live Performance Demo
# subtitle: Lorem ipsum dolor sit amet, consectetur adipisicing elit.
description: This video demo combines visuals created in Unreal engine with a Dolby Atmos mix of an original composition by Jacob Cooper.

image: https://res.cloudinary.com/dhwvtuay6/image/upload/v1705938665/MV_4kSnapshot2_xqsqod.png
optimized_image: https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_360/v1705507835/IMG_4783_rlophx.jpg
category: music
tags:
  - ambisonics
  - motion capture
  - music performance
author: Jacob Cooper
---

This series of webpages provides an account of the audiovisual workflows used to produce three different immersive pieces as part of the [Developing a Database of Immersive Audiovisual Materials](https://audiolab.york.ac.uk/developing-a-database-of-immersive-audiovisual-materials/) project:

- Maida Vale live performance demo
- Macbeth demo
- Spatialised speech demo

Each of these demos showcases a different context for immersive audiovisual media. The first looks at live music performance; the second, more traditional film and television content; and the third, a more abstract / artistic use.

All were created through combining spatial audio workflows and motion-capture technologies in slightly different ways that will be explored through this series of webpages.

This video demo combines visuals created in Unreal engine with a Dolby Atmos mix of an original composition by Jacob Cooper.

<iframe
  id="ytplayer"
  type="text/html"
  width="640"
  height="360"
  src="https://www.youtube.com/embed/Jvrgt98knB4?autoplay=1"
  frameborder="0"
  allowfullscreen
></iframe>

# Audio Workflow

## Recording

A standard multi-track recording workflow was used to record the audio. The images below show the recording setup for the drums.

![Recording setup for drums.](https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507834/IMG_3966_x2yexz.jpg)
<sup>Recording setup for drums.</sup>

<!---![Recording setup for drums (angle 2).](https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507834/IMG_3974_gtie5e.jpg)
<sup>Recording setup for drums (angle 2).</sup>-->

## Mixing

The audio was then mixed in Pro Tools using the Dolby Atmos workflow by Prof. Gavin Kearney. An enhanced stereo scene was presented; the core parts of the mix were presented in stereo, with the additional elements and reverbs being rendered to create a more immersive scene. Due to limitations on the track count, the drums were mixed separately and rendered to a 7.1.2 bed. The audio was rendered to two formats and exported as an Atmos ADM file:
- Binaural
- 7.1.4

The 7.1.4 mix was then encoded to 7th Order Ambisonics using the AmbiX 7th Order panner.

## Deliverable Formats

The audio was provided in the following formats:
- Binaural
- 7.1.4
- 7th Order Ambisonics
- Atmos ADM
- EBU ADM

The BBC’s EAR Production Suite was used to convert the Atmos ADM file to an EBU ADM file. The stems were also provided separately.

# Visual Workflow

The visuals were constructed using the following:
- Environment modelling using SketchUp
- Motion-tracking captured using:
    - Vicon system
    - XSens system
- Face-tracking captured using LiveLink Face For Unreal Engine
- 3D scanning of instruments
- Project assembly using Unreal Engine 5

## Environment Modelling

Model of Maida Vale Studio 4 [1] was created in SketchUp and exported as a .dae 3D model.

![Model of Maida Vale Studio 4.](https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507836/LR_Internal_Lower_rvog2t.png)
<sup>Model of Maida Vale Studio 4.</sup>

## Motion-Tracking

### Guitar/ Keyboard Tracking

A Vicon motion-tracking system was used to capture the performer and instrument positions for the following:

- Bass
- Rhythm guitar
- Lead guitar and lead synth

![Performer playing guitar in a motion-capture suit.](https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507834/DSC00172_javoid.jpg)
<sup>Performer playing guitar in a motion-capture suit.</sup>

![Finger-tracking using motion-capture markers.](https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507833/DSC00154_hwybxj.jpg)
<sup>Finger-tracking using motion-capture markers.</sup>

The performer was captured playing along with the track. To sync this with the audio, the performer strummed along to a 1-bar count in before the track started. Full body and finger tracking was used; finger-tracking made playing near-impossible. The synth keyboard was not tracked as it remained in the same position.

Instruments were tracked using 5 motion-capture markers.

### Drum Tracking - XSens

Initially, drum tracking was done using an XSens suit; sticks were tracked using markers. This didn’t facilitate the tracking of cymbals. The drummer clicked their sticks along with the 1-bar count in.

![Performer playing drums whilst wearing an XSens suit.](https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507835/IMG_4783_rlophx.jpg)
<sup>Performer playing drums whilst wearing an XSens suit.</sup>

### Drum Tracking II - Vicon

The drum tracking was re-recorded to allow for the capture of moving cymbals. Instead of an acoustic kit, an electric kit was played, with markers placed on the rubber cymbals. Fingers were not fully tracked for the drummer.

<iframe
  src="https://player.cloudinary.com/embed/?public_id=joe_drums&cloud_name=dhwvtuay6"
  width="640"
  height="360" 
  style="height: auto; width: 100%; aspect-ratio: 640 / 360;"
  allow="autoplay; fullscreen; encrypted-media; picture-in-picture"
  allowfullscreen
  frameborder="0"
></iframe>
<sup>Performer playing drums whilst wearing a Vicon suit.</sup>

## Face-Tracking

Face-tracking was recorded using the LiveLink Face for Unreal application for Apple devices (with True Depth camera). A short extract of the performer playing (< 30 seconds) was recorded and looped during the video.

## 3D Scanning

Instruments were scanned using an Artec 3D scanner - due to issues with reflective surfaces, the models were poor quality, and as such, were not used.

## Project Assembly

The model and tracking data were combined in Unreal Engine 5; all tracking data was mapped to metahumans and they were placed within a virtual Maida Vale studio 4. Downloaded instrument assets were used for the guitars, bass and synth (keyboard).

Unreal’s ‘Sequencer’ was used to put the project together. Cameras were placed inside the virtual space to capture the video.

# Credits

### Composition, Recording & Production

Jacob Cooper

### Mixing

Gavin Kearney

### Musical Performance

Andrew Chadwick - Drums

Jacob Cooper - All Other Instruments

### Motion-Capture Performance

Joe-Rees Jones - Drums

Jacob Cooper - All Other Instruments

### Visuals

Joe Rees-Jones & Jacob Cooper

# Asset Licences

- Drum Kit: “Drum Kit” by Serg.Morgun is licensed under CC BY 4.0 ([https://sketchfab.com/3d-models/drum-kit-99218427e7a2424ea8afc9b8c668a5c7](https://sketchfab.com/3d-models/drum-kit-99218427e7a2424ea8afc9b8c668a5c7))
- Bass: Obtained from SketchFab (now removed) is licensed under CC BY 4.0
- Rhythm Guitar: “Fender Stratocaster Guitar” by Ryan_Nein is licensed under CC BY 4.0 ([https://sketchfab.com/3d-models/fender-stratocaster-guitar-15a37147641b4c1b963bb494b234593f](https://sketchfab.com/3d-models/fender-stratocaster-guitar-15a37147641b4c1b963bb494b234593f))
- Lead Guitar: “Guitar” by Matterhorn is licensed under CC BY 4.0 ([https://sketchfab.com/3d-models/guitar-f1a304bb87304049b03c1447ce9eb96f](https://sketchfab.com/3d-models/guitar-f1a304bb87304049b03c1447ce9eb96f))
- Keyboard Stand: Adapted from “Keyboard X-Stand” by Michael Perez which is licensed under CC BY 4.0 ([https://sketchfab.com/3d-models/keyboard-x-stand-d76fd9cba4234dd1891581c2df6b7b00](https://sketchfab.com/3d-models/keyboard-x-stand-d76fd9cba4234dd1891581c2df6b7b00))
- Stage Lights: “Box Panel Spot Light” by Photoant77 is licensed under CC BY 4.0 ([https://sketchfab.com/3d-models/box-panel-spot-light-ddd17f352a024e7ab2722aa1e97e5a47](https://sketchfab.com/3d-models/box-panel-spot-light-ddd17f352a024e7ab2722aa1e97e5a47))

# References

[1] - Cairns, P, Hunt, A, Cooper, J, Johnston, D, Lee, B, Daffern, H & Kearney, G 2022, 'Recording Music in the Metaverse', Paper presented at Audio Engineering Society Conference: AES 2022 International Audio for Virtual and Augmented Reality Conference, Redmond, United States, 15/08/22 - 17/08/22.