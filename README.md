<div id="top"></div>

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



<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">Promtail - Pharm-IT</h3>

  <p align="center">
    Pre-configured Promtail Agent by Pharm-IT for monitoring use.
    <br />
    <a href="https://grafana.com/docs/loki/latest/clients/promtail/"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://github.com/pharm-it-de/promtail-pharmit/issues">Report Bug</a>
    ·
    <a href="https://github.com/pharm-it-de/promtail-pharmit/issues">Request Feature</a>
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
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This is a pre-configured `Promtail client` by Pharm-IT to send logs to Grafana.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Grafana's Promtail client](https://grafana.com/docs/loki/latest/clients/promtail/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Because the project is dockerized, you can run the following command to start the `Promtail Client` instance.

### Installation

1. Install [Docker](https://docs.docker.com/engine/install/) and [Docker Compose](https://docs.docker.com/compose/install/)
2. Clone the repo
   ```sh
   git clone https://github.com/pharm-it-de/promtail-pharmit.git
   ```
3. Create the `.env`-file (you can create a new API Key [here](https://grafana.com/docs/loki/latest/clients/promtail/).
   ```sh
    # The URL to the Loki Server (either local or on Grafana Cloud)
    CLIENT_URL=<CLIENT_URL>
   ```
4. Run the docker containers
   ```sh
   docker-compose up -d
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Project Link: [https://github.com/pharm-it-de/promtail-pharmit](https://github.com/pharm-it-de/promtail-pharmit)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/pharm-it-de/promtail-pharmit.svg?style=for-the-badge
[contributors-url]: https://github.com/pharm-it-de/promtail-pharmit/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/pharm-it-de/promtail-pharmit.svg?style=for-the-badge
[forks-url]: https://github.com/pharm-it-de/promtail-pharmit/network/members
[stars-shield]: https://img.shields.io/github/stars/pharm-it-de/promtail-pharmit.svg?style=for-the-badge
[stars-url]: https://github.com/pharm-it-de/promtail-pharmit/stargazers
[issues-shield]: https://img.shields.io/github/issues/pharm-it-de/promtail-pharmit.svg?style=for-the-badge
[issues-url]: https://github.com/pharm-it-de/promtail-pharmit/issues
[license-shield]: https://img.shields.io/github/license/pharm-it-de/promtail-pharmit.svg?style=for-the-badge
[license-url]: https://github.com/pharm-it-de/promtail-pharmit/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/pharm-it-de