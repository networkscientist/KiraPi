<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![AGPL License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/networkscientist/KiraPi">
    <img src="images/logo.svg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">KiraPi</h3>

  <p align="center">
    The KiraPi system was created as part of the Seminar Geodata Analysis. It currently monitors air temperature as well as the relative humidity of the air through a DHT22 sensor. Furthermore, the collected data is represented in graphs. The project is built on top of a Raspberry Pi system and coded in Python3.
    <br />
    <a href="https://github.com/networkscientist/KiraPi/wiki"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/networkscientist/KiraPi">View Demo</a>
    ·
    <a href="https://github.com/networkscientist/KiraPi/issues">Report Bug</a>
    ·
    <a href="https://github.com/networkscientist/KiraPi/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `email`, `email_client`,

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Python3](https://python.org/)
* [Raspbian](https://raspbian.org)
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Set up the Raspberry Pi with Python3
2. Connect the DHT22 sensor with the Raspberry Pi. Take a note of the BCM pin where the sensor is attached.
3. Clone the repo
   ```sh
   git clone https://github.com/networkscientist/KiraPi.git
   ```
4. Update the BCM pin number in `main.py` to match your setting
    ```python
    ## Initial Values
    gpio = 4 # BCM Numbering
    ```
5. Update the path where your log file should be stored in `dht22.py`
    ```python
    ## Initial Values
    csv_path = "/home/pi/KiraPi/output/sens.txt" # Where the measurements will be stored
    ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [] Feature 1
- [] Feature 2
- [] Feature 3
    - [] Nested Feature

See the [open issues](https://github.com/networkscientist/KiraPi/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU Affero General Public License v3.0. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Peter Zweifel - email@email_client.com

Project Link: [https://github.com/networkscientist/KiraPi](https://github.com/networkscientist/KiraPi)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [README Template](https://github.com/othneildrew/Best-README-Template)
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/networkscientist/KiraPi.svg?style=for-the-badge
[contributors-url]: https://github.com/networkscientist/KiraPi/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/networkscientist/KiraPi.svg?style=for-the-badge
[forks-url]: https://github.com/networkscientist/KiraPi/network/members
[stars-shield]: https://img.shields.io/github/stars/networkscientist/KiraPi.svg?style=for-the-badge
[stars-url]: https://github.com/networkscientist/KiraPi/stargazers
[issues-shield]: https://img.shields.io/github/issues/networkscientist/KiraPi.svg?style=for-the-badge
[issues-url]: https://github.com/networkscientist/KiraPi/issues
[license-shield]: https://img.shields.io/github/license/networkscientist/KiraPi.svg?style=for-the-badge
[license-url]: https://github.com/networkscientist/KiraPi/blob/master/LICENSE.txt
[product-screenshot]: images/screenshot.png
