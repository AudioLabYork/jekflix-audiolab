---
# date: 2010-09-10 12:26:40
layout: post
title: York - Huddersfield Networked Performance
subtitle: This dataset contains audio and video materials recorded during a networked music performance which took place on 22.08.2023 between the Univesity of York and University of Huddersfield.
description: This dataset contains audio and video materials recorded during a networked music performance which took place on 22.08.2023 between the Univesity of York and University of Huddersfield.
image: https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1706002021/Image_20230821_200824_022_ul5uky.jpg
optimized_image: https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_360/v1706002021/Image_20230821_200824_022_ul5uky.jpg
category: music
tags:
  - audio
  - ambisonics
  - music
author: Tomasz Rudzki
---

<!-- This dataset contains audio and video materials recorded during a networked music performance which took place on 22.08.2023 between the Univesity of York and University of Huddersfield. -->

## Network Setup
Phipp's Hall, University of Huddersfield, and the AudioLab, University of York, were connected over the internet using the existing academic internet access at each endpoint (JANET). [JackTrip](https://ccrma.stanford.edu/software/jacktrip/) was used to stream audio between endpoints, and [JACK](https://jackaudio.org/) was used to route audio between JackTrip and hardware capture/playback buffers. A full system throughput latency of approximately 16ms was achieved. Local Mic capture and JackTrip receive channels were recorded at each endpoint.

<figure>
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_scale,w_800/v1706625965/saffire-york-huddersfield-map_kndz0t.png">
  <figcaption>Simplified map of the system.</figcaption>
</figure>


<!-- Link for JackTrip:
https://ccrma.stanford.edu/software/jacktrip/

Pub for JackTrip:
https://doi.org/10.1080/09298215.2010.481361

Link for JACK:
https://jackaudio.org/ -->


## Spatial Audio Production Workflow

Based on the time-aligned stems from the performance, two selected pieces were mixed in 7th-order Ambisonics. The virtual singer postions were uniformly distributed in front of the listener in a perfect half-circle.

<figure>
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_crop,g_center,w_1040,h_720/v1706018008/src_rec_floor_plan_zk6xbw.png">
  <figcaption>Positions of the singers and the listener in the room acoustics simulation.</figcaption>
</figure>

### Virtual Acoustics

Early reflections and late reverberation were added based on a simulation of BBC Maida Vale Studio 2 room.

<figure>
  <img src="https://res.cloudinary.com/dhwvtuay6/image/upload/c_crop,g_center,w_880,h_650/v1706018007/simulated-RT-check_xkbuyx.png">
  <figcaption>Comparison of reverberation times measured in Maida Vale Studio 2 and simulated one.</figcaption>
</figure>

The binaural files were rendered using MagLS filters calculated from SADIE II KU100 HRTFs.


### Used Tools
* [Reaper DAW](https://www.reaper.fm/)
* [MCRoomSim](https://github.com/Andronicus1000/MCRoomSim)
* [mcfx convolver](https://github.com/kronihias/mcfx)
* [aXEqualizer](https://www.ssa-plugins.com/plugins/axequalizer/)
* [aXCompressor](https://www.ssa-plugins.com/plugins/axcompressor/)

## Downloads

<table>
<thead>
  <tr>
    <th>Title</th>
    <th>Composer</th>
    <th>Format</th>
    <th>Filetype</th>
    <th>Download</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">Laudate Dominum Omnes Gentes</td>
    <td rowspan="2">Tomas Luis de Victoria</td>
    <td>7th Order Ambisonics (ACN/SN3D)</td>
    <td>WAV</td>
    <td><a href="https://zenodo.org/records/10402916/files/01-Ex_Corde_-_Laudate_Dominum_Omnes_Gentes_(Tomas_Luis_de_Victoria)-7OA.wav?download=1">LINK</a></td>
  </tr>
  <tr>
    <td>Binaural</td>
    <td>WAV</td>
    <td><a href="https://zenodo.org/records/10402916/files/01-Ex_Corde_-_Laudate_Dominum_Omnes_Gentes_(Tomas_Luis_de_Victoria)-Binaural.wav?download=1">LINK</a></td>
  </tr>
  <tr>
    <td rowspan="2">Tutto Lo Di</td>
    <td rowspan="2">Orlando Di Lasso</td>
    <td>7th Order Ambisonics (ACN/SN3D)</td>
    <td>WAV</td>
    <td><a href="https://zenodo.org/records/10402916/files/02-Ex_Corde_-_Tutto_Lo_Di_(Orlando_Di_Lasso)-7OA.wav?download=1">LINK</a></td>
  </tr>
  <tr>
    <td>Binaural</td>
    <td>WAV</td>
    <td><a href="https://zenodo.org/records/10402916/files/02-Ex_Corde_-_Tutto_Lo_Di_(Orlando_Di_Lasso)-Binaural.wav?download=1">LINK</a></td>
  </tr>
</tbody>
</table>

## Credits

### Musical Performance
[Ex Corde Vocal Ensemble](https://www.excordevocal.com/)

### Recording & Production
Helena Daffern, Andrew Chadwick, Patrick Cairns, Jacob Cooper, Tomasz Rudzki

### Networking
Patrick Cairns

### Spatial Audio Mixing
Tomasz Rudzki, Jacob Cooper

### Funding
EPSRC Impact Acceleration Account (EP/X525856/1) funded project SAFFIRE, in part by the UK AHRC XR Stories project, grant no. AH/S002839/1


