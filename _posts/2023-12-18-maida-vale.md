---
# date: 2010-09-10 12:26:40
layout: post
title: Maida Vale Live Performance Demo
subtitle: This video demo combines visuals created in Unreal engine with a Dolby Atmos mix of an original composition by Jacob Cooper.
description: This video demo combines visuals created in Unreal engine with a Dolby Atmos mix of an original composition by Jacob Cooper.

#image: https://res.cloudinary.com/dhwvtuay6/image/upload/v1705938665/MV_4kSnapshot2_xqsqod.png
optimized_image: https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_360/v1705938665/MV_4kSnapshot2_xqsqod.png
category: music
tags:
  - ambisonics
  - motion capture
  - music
  - audio
  - visual
author: Jacob Cooper
---

<iframe
  id="ytplayer"
  type="text/html"
  width="640"
  height="360"
  src="https://www.youtube.com/embed/Jvrgt98knB4?autoplay=0"
  frameborder="0"
  allowfullscreen
></iframe>

## Audio Workflow

### Recording

A standard multi-track recording workflow was used to record the audio. The images below show the recording setup for the drums.

<figure>
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_700/v1705507834/IMG_3966_x2yexz.jpg">
  <figcaption>Recording setup for drums.</figcaption>
</figure>

<!---![Recording setup for drums (angle 2).](https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507834/IMG_3974_gtie5e.jpg)
<sup>Recording setup for drums (angle 2).</sup>-->

### Mixing

The audio was then mixed in Pro Tools using the Dolby Atmos workflow by Prof. Gavin Kearney. An enhanced stereo scene was presented; the core parts of the mix were presented in stereo, with the additional elements and reverbs being rendered to create a more immersive scene. Due to limitations on the track count, the drums were mixed separately and rendered to a 7.1.2 bed. The audio was rendered to two formats and exported as an Atmos ADM file:
- Binaural
- 7.1.4

The 7.1.4 mix was then encoded to 7th Order Ambisonics using the AmbiX 7th Order panner.

### Deliverable Formats

The audio was provided in the following formats:
- Binaural
- 7.1.4
- 7th Order Ambisonics
- Atmos ADM
- EBU ADM

The BBC’s EAR Production Suite was used to convert the Atmos ADM file to an EBU ADM file. The stems were also provided separately.

## Visual Workflow

The visuals were constructed using the following:
- Environment modelling using SketchUp
- Motion-tracking captured using <b>Vicon</b> & <b>XSens</b> systems
- Face-tracking captured using LiveLink Face For Unreal Engine
- 3D scanning of instruments
- Project assembly using Unreal Engine 5

### Environment Modelling

Model of Maida Vale Studio 4 [1] was created in SketchUp and exported as a .dae 3D model.

<figure>  
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_700/v1705507836/LR_Internal_Lower_rvog2t.png">
  <figcaption>Model of Maida Vale Studio 4.</figcaption>
</figure>

### Motion-Tracking

#### Guitar/ Keyboard Tracking

A Vicon motion-tracking system was used to capture the performer and instrument positions for the following:

- Bass
- Rhythm guitar
- Lead guitar and lead synth

<figure>  
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_700/v1705507834/DSC00172_javoid.jpg">
  <figcaption>Performer playing guitar in a motion-capture suit</figcaption>
</figure>

<figure>  
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_700/v1705507833/DSC00154_hwybxj.jpg">
  <figcaption>Finger-tracking using motion-capture markers.</figcaption>
</figure>

The performer was captured playing along with the track. To sync this with the audio, the performer strummed along to a 1-bar count in before the track started. Full body and finger tracking was used; finger-tracking made playing near-impossible. The synth keyboard was not tracked as it remained in the same position.

Instruments were tracked using 5 motion-capture markers.

#### Drum Tracking - XSens

Initially, drum tracking was done using an XSens suit; sticks were tracked using markers. This didn’t facilitate the tracking of cymbals. The drummer clicked their sticks along with the 1-bar count in.

<figure>  
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1705507835/IMG_4783_rlophx.jpg">
  <figcaption>Performer playing drums whilst wearing an XSens suit.</figcaption>
</figure>

#### Drum Tracking II - Vicon

The drum tracking was re-recorded to allow for the capture of moving cymbals. Instead of an acoustic kit, an electric kit was played, with markers placed on the rubber cymbals. Fingers were not fully tracked for the drummer.

<figure>  
  <iframe
    src="https://player.cloudinary.com/embed/?public_id=joe_drums&cloud_name=dhwvtuay6"
    width="640"
    height="360" 
    style="height: auto; width: 100%; aspect-ratio: 640 / 360;"
    allow="autoplay; fullscreen; encrypted-media; picture-in-picture"
    allowfullscreen
    frameborder="0"
  ></iframe>
  <figcaption><br>Performer playing drums whilst wearing an XSens suit.</figcaption>
</figure>

### Face-Tracking

Face-tracking was recorded using the LiveLink Face for Unreal application for Apple devices (with True Depth camera). A short extract of the performer playing (< 30 seconds) was recorded and looped during the video.

### 3D Scanning

Instruments were scanned using an Artec 3D scanner - due to issues with reflective surfaces, the models were poor quality, and as such, were not used.

### Project Assembly

The model and tracking data were combined in Unreal Engine 5; all tracking data was mapped to metahumans and they were placed within a virtual Maida Vale studio 4. Downloaded instrument assets were used for the guitars, bass and synth (keyboard).

Unreal’s ‘Sequencer’ was used to put the project together. Cameras were placed inside the virtual space to capture the video.

## Credits

The AudioLab would like to thank Google for their collaboration with, and funding of this project.

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

### Asset Licences

<sup>Drum Kit: “[Drum Kit](https://sketchfab.com/3d-models/drum-kit-99218427e7a2424ea8afc9b8c668a5c7)” by Serg.Morgun is licensed under CC BY 4.0</sup><br>
<sup>Bass: Obtained from SketchFab (now removed) is licensed under CC BY 4.0</sup><br>
<sup>Rhythm Guitar: “[Fender Stratocaster Guitar](https://sketchfab.com/3d-models/fender-stratocaster-guitar-15a37147641b4c1b963bb494b234593f)” by Ryan_Nein is licensed under CC BY 4.0</sup><br>
<sup>Lead Guitar: “[Guitar](https://sketchfab.com/3d-models/guitar-f1a304bb87304049b03c1447ce9eb96f)” by Matterhorn is licensed under CC BY 4.0</sup><br>
<sup>Keyboard Stand: Adapted from “[Keyboard X-Stand](https://sketchfab.com/3d-models/keyboard-x-stand-d76fd9cba4234dd1891581c2df6b7b00)” by Michael Perez which is licensed under CC BY 4.0</sup><br>
<sup>Stage Lights: “[Box Panel Spot Light](https://sketchfab.com/3d-models/box-panel-spot-light-ddd17f352a024e7ab2722aa1e97e5a47)” by Photoant77 is licensed under CC BY 4.0</sup>

## References

<sup>[1] - Cairns, P, Hunt, A, Cooper, J, Johnston, D, Lee, B, Daffern, H & Kearney, G 2022, 'Recording Music in the Metaverse', Paper presented at Audio Engineering Society Conference: AES 2022 International Audio for Virtual and Augmented Reality Conference, Redmond, United States, 15/08/22 - 17/08/22.</sup>