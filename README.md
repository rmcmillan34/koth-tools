<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/rmcmillan34/koth-tools">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">KotH Tools</h3>

  <p align="center">
    A writeup of King of the Hill/Attack & Defence style CTF tips and techniques, along with some helpful scripts to use during gameplay.
    <br />
    <a href="https://github.com/rmcmillan34/koth-tools"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/rmcmillan34/koth-tools">View Demo</a>
    ·
    <a href="https://github.com/rmcmillan34/koth-tools/issues">Report Bug</a>
    ·
    <a href="https://github.com/rmcmillan34/koth-tools/issues">Request Feature</a>
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

### Built With

* Bash
* Markdown


### KotH Write-up

### Scripts

#### Randomiser

[![Randomiser Script Screen Shot][randomiser-screenshot]](https://github.com/rmcmillan34/koth-tools)
Randomiser script in use

#### Ghost-Writer

[![Ghost-writer Script Screen Shot][ghost_writer-screenshot]](https://github.com/rmcmillan34/koth-tools)
Ghost_writer script in action

#### ASSHHOLE

#### Portal

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- GETTING STARTED -->
## Getting Started

To use the scripts in this repo please do the following:

### Prerequisites

The scripts contained in this repo are designed to be run as root from the target machine. 
As such they should be uploaded to and marked as executable on the target machine

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/rmcmillan34/koth-tools.git
   ```
3. Host scripts to be uploaded to target machine (with Python SimpleHTTPServer for example)
   ```sh
   sudo python3 -m SimpleHTTPServer 80
   ```
4. Download script from target machine
   ```sh
   wget http://{HTTP_SERVER_IP}:80
   ```
5. Set scripts as executable
   ```sh
   sudo chmod +x {SCRIPT_NAME}
   ```
6. Run the script
   ```sh
   ./{SCRIPT_NAME}
   ```
   
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] KotH Write-up
- [ ] ASSHHOLE Script
- [ ] Portal Script
- [ ] Python REPL (Read Evaluate Print Loop)

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Ryan McMillan - Twitter:[@RizzSec](https://twitter.com/RizzSec)

Project Link: [https://github.com/rmcmillan34/koth-tools](https://github.com/rmcmillan34/koth-tools)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [othnieldrew](https://github.com/othnieldrew/Best-README-Template) - README Template
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/rmcmillan34/koth-tools.svg?style=for-the-badge
[contributors-url]: https://github.com/rmcmillan34/koth-tools/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rmcmillan34/koth-tools.svg?style=for-the-badge
[forks-url]: https://github.com/rmcmillan34/koth-tools/network/members
[stars-shield]: https://img.shields.io/github/stars/rmcmillan34/koth-tools.svg?style=for-the-badge
[stars-url]: https://github.com/rmcmillan34/koth-tools/stargazers
[issues-shield]: https://img.shields.io/github/issues/rmcmillan34/koth-tools.svg?style=for-the-badge
[issues-url]: https://github.com/rmcmillan34/koth-tools/issues
[license-shield]: https://img.shields.io/github/license/rmcmillan34/koth-tools.svg?style=for-the-badge
[license-url]: https://github.com/rmcmillan34/koth-tools/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/ryan-mcmillan34
[randomiser-screenshot]: images/randomiser.png
[ghost_writer-screenshot]: images/ghost_writer.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
