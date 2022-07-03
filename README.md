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
[![GPL-3.0][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <p>
    <img src="https://raw.githubusercontent.com/RudigerMorinDocter/MISP-GameCheats/main/MISP_GameCheats_SmallSkull_Logo.png" alt="GameCheats_Logo" height="200">
    &emsp;
	<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Misp-logo.png" alt="MISP_Logo" width="265" height="200">
  </p>

  <h1 align="center">MISP - Game Cheat</h1>
  
  <p align="center">
   Implementation of a MISP object capable of describing a video game cheat application.<br />
   The goal is to expand the collection of objects in the MISP project, since cheatware is often linked to malware, especially when it is distributed for free.
    <br />
    <a href="https://github.com/RudigerMorinDocter/MISP-GameCheats"><strong>Check the repository »</strong></a>
    <br />
    <a href="https://www.misp-project.org/documentation/"><strong>Explore the docs »</strong></a>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary><u>Table of Contents :</u></summary>
  <ol>
    <li>
      <a href="#about-the-misp-project">About The MISP Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#misp-gamecheat-object">MISP GameCheats Object</a></li>
    <ul>
        <li><a href="#gamecheat-object-fields">GameCheat Object Fields</a></li>
      </ul>
      <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#useless-but-fun">Useless but fun</a></li>
  </ol>
</details>


<!-- ABOUT THE MISP PROJECT -->
## About The MISP Project

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![product-screenshot]](https://www.misp-project.org/)
<p align="left">
MISP is an open source software solution for collecting, storing, distributing and sharing cyber security indicators and threats about cyber security incidents analysis and malware analysis. MISP is designed by and for incident analysts, security and ICT professionals or malware reversers to support their day-to-day operations to share structured information efficiently.

The objective of MISP is to foster the sharing of structured information within the security community and abroad. MISP provides functionalities to support the exchange of information but also the consumption of said information by Network Intrusion Detection Systems (NIDS), LIDS but also log analysis tools, SIEMs ...
</p>
For more information checkout official [MISP Github Repository](https://github.com/MISP).

### Built With

* [MISP Documentation](https://www.misp-project.org)
* [Google Search Bar](https://www.google.com)
* [Wikipedia EN - Cheating in video games](https://en.wikipedia.org/wiki/Cheating_in_video_games)
* [Wikipedia EN - Cheating in online games](https://en.wikipedia.org/wiki/Cheating_in_online_games)
* [Wikipedia FR - Cheat](https://fr.wikipedia.org/wiki/Cheat)
* [Toilet Paper ???](http://papertoilet.com/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- Object Description -->
## MISP GameCheat Object
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![project-logo]](https://github.com/RudigerMorinDocter/MISP-GameCheats)

As stated in the introduction, the goal of this object is to implement a new MISP object describing a video game cheat application (called "Game Cheat" in our repository).

The idea that lead us to create such an object is that game cheats and/or cheatware is often linked to malware, especially when it is distributed for free. Since the MISP project does not seem to have this kind of object implemented yet, it could be used as a base for future improvement and use by the community.

As the subject of game cheats is extremely wide, we encourage anyone who has the courage to fork our repository and continue our work ! ☠️

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Object fields description -->
### GameCheat Object Fields
Here we will quickly describe the technical implementation of our MISP object. You can check out the full object by looking at the `definition.json` file ! 👾

***MISP Object name :*** `game-cheat` - *Describes a game cheat or cheatware.*

***Attributes :***
* `cheat-name` : *Known name of the game cheat, if given.*
* `cheat-type` : *Select a type of cheat (from a dropdown menu).*
* `ig-cheat-behaviour` : *Describe the in-game behaviour of the cheat (e.g. You selected 'Aim Bot', here you can add details like 'Activate by pressing F7, Deactivate by pressing F8. Not detected be Easy Anti-Cheat.')".*
* `cheat-version` : *Any information about the cheatware version.*
* `affected-game` : *Name of the game that is targeted by the cheatware.*
* `pricing` : *Cheatware price, 0 if free.*
* `compilation-date` : *Compilation date of the game cheat, if known.*
* `implementation` : *How the cheatware is implemented (from a dropdown menu).*
* `implementation-details` : *Additionnal informations about the implementation of the cheatware. (e.g. Requires to swap a dll file.)*
* `operating-system` : *Operating system required and its version.*
* `creator` : *Individual and/or Group and/or Organization that created the cheat.*
* `webpage` : *Place where the cheat is promoted. Website, Forum, Download page, ...*
* `cheat-screenshot` : *Screenshot of the cheat at work.*

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [X] Check if similar object exists in MISP Project (in does not).
- [X] Creation of new object based on existing templates.
- [X] Adding useful content...
- [X] Finalizing work and correction of typos.
- [x] Validation by the MISP team in charge of the project.
- [x] Integration of object to the MISP Project !

See the [open issues](https://github.com/RudigerMorinDocter/MISP-GameCheats/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request !

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->
## License
Distributed under the :cow: `GNU GPL-3.0` (https://www.gnu.org/licenses/gpl-3.0.en.html).
See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

* :turtle: USTA Enes - [@Github](https://github.com/enes-usta)
* :snail: Rüdiger Morin-Docter - [@Github](https://github.com/RudigerMorinDocter)

Project Link: [MISP-GameCheats](https://github.com/RudigerMorinDocter/MISP-GameCheats)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
Great teachers and great people ;)
* Alexandre Dulaunoy - [@Github](https://github.com/adulau)
* VINOT Raphaël - [@Github](https://github.com/Rafiot)

<p align="right">(<a href="#top">back to top</a>)</p>


## Useless but fun
---> :snail: Want to feel like a h@cker ? - [Here you go](https://hackertyper.com/)

<br /><br /><br /><br /><br /><br /><br /><br /><br />

Bzz Bzz I'm a Honey Bee ! :honeybee:
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/RudigerMorinDocter/MISP-GameCheats
[contributors-url]: https://github.com/RudigerMorinDocter/MISP-GameCheats/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/RudigerMorinDocter/MISP-GameCheats
[forks-url]: https://github.com/RudigerMorinDocter/MISP-GameCheats/network
[stars-shield]: https://img.shields.io/github/stars/RudigerMorinDocter/MISP-GameCheats?color=ff69b4
[stars-url]: https://github.com/RudigerMorinDocter/MISP-GameCheats/stargazers
[issues-shield]: https://img.shields.io/github/issues/RudigerMorinDocter/MISP-GameCheats
[issues-url]: https://github.com/RudigerMorinDocter/MISP-GameCheats/issues
[license-shield]: https://img.shields.io/github/license/RudigerMorinDocter/MISP-GameCheats
[license-url]: https://github.com/RudigerMorinDocter/MISP-GameCheats/blob/main/LICENSE
[project-logo]: https://raw.githubusercontent.com/RudigerMorinDocter/MISP-GameCheats/main/MISP_GameCheats_SmallSkull_Logo.png
[product-screenshot]: https://upload.wikimedia.org/wikipedia/commons/9/91/Misp-logo.png
