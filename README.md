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



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/n3ddu8/nest-cli">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">nest-cli</h3>

  <p align="center">
    Distrobox/Toolbox implementation of my custom Alpine development environment built using the [nest](https://github.com/n3ddu8/nest) instruction set.
    <br />
    <br />
    <a href="https://github.com/n3ddu8/nest-cli/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/n3ddu8/nest-cli/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

...

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [ublue-os/boxkit](https://github.com/ublue-os/boxkit)
* [Just](https://just.systems/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* [Distrobox](https://distrobox.it/)

```shell
curl -s https://raw.githubusercontent.com/89luca89/distrobox/main/install | sudo sh
```

### Installation

For Distrobox:
```shell
distrobox create -i ghcr.io/n3ddu8/nest-cli -n nest
distrobox enter nest
```

For Toolbox:
```shell
toolbox create -i ghcr.io/n3ddu8/nest-cli -c nest
toolbox enter nest
```

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



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

<a href="https://github.com/ublue-os/boxkit" title="ublue-os/boxkit">Forked from ublue-os/boxkit</a>

<a href="https://www.flaticon.com/free-icons/container" title="container icons">Container icons created by Freepik - Flaticon</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/n3ddu8/nest-cli.svg?style=for-the-badge
[contributors-url]: https://github.com/n3ddu8/nest-cli/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/n3ddu8/nest-cli.svg?style=for-the-badge
[forks-url]: https://github.com/n3ddu8/nest-cli/network/members
[stars-shield]: https://img.shields.io/github/stars/n3ddu8/nest-cli.svg?style=for-the-badge
[stars-url]: https://github.com/n3ddu8/nest-cli/stargazers
[issues-shield]: https://img.shields.io/github/issues/n3ddu8/nest-cli.svg?style=for-the-badge
[issues-url]: https://github.com/n3ddu8/nest-cli/issues
[license-shield]: https://img.shields.io/github/license/n3ddu8/nest-cli.svg?style=for-the-badge
[license-url]: https://github.com/n3ddu8/nest-cli/blob/master/LICENSE.txt
