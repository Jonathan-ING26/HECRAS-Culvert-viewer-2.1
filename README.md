# HECRAS-Culvert-viewer-2.1

<p align="left">
  <img align="left" width="166" height="187"
       src="https://github.com/user-attachments/assets/735cfd2d-7b47-453c-9360-e35194aa3781">

  This application allows users to visualize the profile of a culvert<br>
  across a Digital Terrain Model (DTM) for any culvert configured<br>
  through a SA 2D Connection in HEC-RAS.<br><br>

  It helps engineers quickly verify terrain integration,<br>
  identify potential geometric issues and export profile views<br>
  for reporting purposes.
</p>
<br clear="left"/>

## Overview

When using culverts through 2D SA Connections in HEC-RAS, it can be difficult to quickly verify how the structure is integrated within the terrain. While HEC-RAS provides all the necessary data, a dedicated profile visualization is not readily available.

This tool reads HEC-RAS geometry files (.gxx) together with the associated terrain (.vrt) files and reconstructs culverts in profile, providing a quick and intuitive way to review their implementation.

<img width="2048" height="1075" alt="1780052323216" src="https://github.com/user-attachments/assets/9a403fc4-6a1b-43fc-b85b-1e90e7dad4fc" />


## Main Features

- Automatic synchronization with the most recently opened HEC-RAS project
- Automatic discovery of geometry and terrain files
- Culvert analysis:
  - Upstream and downstream invert elevations
  - Slope
  - Length
  - Terrain elevations
- Detection of potential inconsistencies:
  - Excessive slopes
  - Terrain interference with the culvert
- Profile visualization:
  - Terrain profile
  - Culvert geometry
  - Weir representation
- Adjustable upstream and downstream terrain extent
- CAD-style display mode for reports and studies
- Export capabilities:
  - PNG images
  - Batch image export
  - CSV tables
- Light and dark themes
- English and French interface

## Intended Use

This tool is intended to assist hydraulic engineers and HEC-RAS users during model review and quality control.

It is not intended to replace engineering judgement or HEC-RAS itself.

## Installation

1. Download the latest release.
2. Extract the ZIP archive.
3. Launch the executable.

No installation is required.

## Current Status

This is a personal project developed to address a recurring workflow limitation encountered during hydraulic modelling projects.

The software is actively evolving and feedback is highly appreciated.

## Feedback

Bug reports, suggestions and feature requests are welcome.

If you find the tool useful, feel free to connect and share your feedback.

## Disclaimer

This software is provided "as is", without warranty of any kind. Users remain responsible for verifying all results and ensuring their suitability for engineering applications.

HEC-RAS is a trademark of the U.S. Army Corps of Engineers. This project is independent and is not affiliated with, endorsed by, or supported by the developers of HEC-RAS.

