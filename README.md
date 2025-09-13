# Sphera - Projection Mapping 🌍📽️

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue)](https://www.gnu.org/licenses/gpl-3.0)

## Description

This repository serves as an extension for the Sphera repository, focusing on projection mapping of virtual globe data. It includes configuration files tailored for Splash software (https://splashmapper.xyz/en/), enabling seamless projection mapping. Additionally, the repository provides sphere models with a 0.5 m radius for calibration and projection purposes.

## Table of Contents

1.  [Description](#description)
2.  [Features](#features)
3.  [Tech Stack / Key Dependencies](#tech-stack--key-dependencies)
4.  [File Structure Overview](#file-structure-overview)
5.  [Installation](#installation)
6.  [Usage / Getting Started](#usage--getting-started)
7.  [Configuration](#configuration)
8.  [Contributing](#contributing)
9.  [License](#license)
10. [Author/Acknowledgements](#authoracknowledgements)
11. [Contact](#contact)

## Screenshots

![alt text](https://github.com/antoniogojak/sphera-pm/blob/master/Screenshots/20250911_135339.jpg?raw=true)

![alt text](https://github.com/antoniogojak/sphera-pm/blob/master/Screenshots/20250911_170512.jpg?raw=true)

## Features

*   **Projection Mapping Configuration:** Contains configuration files for Splash to facilitate projection mapping.
*   **Sphere Models:** Includes models of spheres with a 0.5 m radius, optimized for calibration and projection.
*   **Sample Earth Texture:** Provides a sample Earth texture for virtual globe projection.

## Tech Stack / Key Dependencies

The primary technologies used in this repository are related to projection mapping and 3D modeling. Key components include:

*   3D modeling project file (Blender)
*   JSON configuration files for projection mapping
*   OBJ models

## Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/antoniogojak/sphera-pm.git
    cd sphera-pm
    ```

2.  Ensure you have Splash installed and configured. Tested with Splash 0.11.2.

3.  Run command prompt from configuration folder and start Splash with

    ```bash
    splash ProjectorDouble_NoCalib.json
    ```

## Usage / Getting Started

1.  Use the provided `.json` configuration files with Splash to set up your projection mapping.
2.  Import the `.obj` sphere models into your preferred 3D software for further customization or adjustments.
3.  Utilize the `Sphere.blend` file in Blender if needed.

## Configuration

The `ProjectorDouble_NoCalib.json` file contains configuration settings for the Splash software. Modify this file to adjust the projection settings as needed.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

Distributed under the GNU General Public License v3.0 License. See `LICENSE` file for more information.

## Author/Acknowledgements

*   Antonio Gojak
*   Earth texture: Natural Earth 3, Tom Patterson ([https://www.shadedrelief.com/natural3/](https://www.shadedrelief.com/natural3/))