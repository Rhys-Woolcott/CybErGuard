<a name="readme-top"></a>




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
![2023-07-30T22:20:51,038110532+02:00](https://github.com/CybErGuard2/CybErGuard/assets/140979451/cbd16767-b896-4711-978f-e2fb5c7b7850)

<br />
<div align="center">

  <h3 align="center">CybErGuard</h3>

  <p align="center">
    Multifunctional Hacking tool!
    <br />
    <a href="https://github.com/CybErGuard2/CybErGuard"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/CybErGuard2/CybErGuard">View Demo</a>
    ·
    <a href="https://github.com/CybErGuard2/CybErGuard/issues">Report Bug</a>
    ·
    <a href="https://github.com/CybErGuard2/CybErGuard/issues">Request Feature</a>
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
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
![2023-07-30T22:19:28,826942258+02:00](https://github.com/CybErGuard2/CybErGuard/assets/140979451/34f8c0d5-e9c7-4dd0-a3aa-25e6a4576f96)


There are many hacking tools out there. But our main goal is to make an easy to use tool for people just getting into hacking. We made sure to make it as simple as possible so even newbies can have fun with it and get motivated to dive deeper into the hacking iceberg.

We think our tool will contribute greatly to newbies or as we call them "skids"

Here's why:
* It's got easy to use syntax and only a small number of commands.
* New features get added really often.
* Cracking passwords and brute-forcing websites has never been easier :smile:
* We even make use of nmap with a single command so "skids" can scan networks easily.

Of course, no hacking tool is going to be useful for everyone. Like I mentioned this is primarily aimed at people who are just starting out. But its a great tool I even use it on my daily tasks since its really smple and saves a lot of time.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

1. Make sure you have a version of Pyhon installed: (https://www.python.org/downloads/)
2. If you want to run networks scans download nmap: (https://nmap.org/)
3. Install all of the python modules listed in the requirements.txt
4. The script will install the other requirements and autiomatically delete them when not needed

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Make sure you have a version of Python installed : (https://www.python.org/downloads/)
2. Clone the repo
   ```sh
   git clone https://github.com/CybErGuard2/CybErGuard
   ```
3. Install python Packages
   ```sh
   pip install -r requirements.txt
   ```
4. Run it
   ```sh
   python3 CybErGuard.py
   ```
   or
   ```sh
   py CybErGuard.py
   ```
5. If you want to run networks scans download nmap: (https://nmap.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

#### *Use ``` help ``` to get a list of the avaliable commands*
#### *Press ```CTRL+C``` to exit any use case and go back to the main menu*

<br>

### Brute-Forcing Websites: 

<img src="https://github.com/CybErGuard2/CybErGuard/assets/140979451/767f2d73-7df9-472c-a7f9-185ca241da1d" alt="Image Description" width="800" height="400"/>


#### *<p> If you dont have a wordlist go: (<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiMmv6tpLeAAxXpSvEDHWWsDIYQFnoECBgQAQ&url=https%3A%2F%2Fgithub.com%2Fbrannondorsey%2Fnaive-hashcat%2Freleases%2Fdownload%2Fdata%2Frockyou.txt&usg=AOvVaw3snAERl1mU6Ccr4WFEazBd&opi=89978449">Download rockyou.txt</a>)</p>*

#### *To brute-force websites run:*

```sh
brute
```

*1.Then you will be prompted for the address of the target, 2.The username for login attempts, 3.A wordlist, 4.And the number of threads you want to use*


<br>
<br>

### Scanning networks: 

<img src="https://github.com/CybErGuard2/CybErGuard/assets/140979451/09af65da-7f6e-4cf1-b6f7-ee3ca28c7c9c" alt="Image Description" width="800" height="400"/>

#### *Make sure you have nmap install on your system (https://nmap.org/)*

#### *To scan networks with CybErGuard run:*

```sh
network
```

*1.Then you wil be prompted to input an ip address, 2.and the amount of ports you want to scan.*

<br>
<br>

### Cracking Hashed Passwords: 

<img src="https://github.com/CybErGuard2/CybErGuard/assets/140979451/5b05fcbb-22bc-41d8-85f9-1a87c3fb462d" alt="Image Description" width="800" height="400"/>

#### <p> If you dont have a wordlist go: (<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiMmv6tpLeAAxXpSvEDHWWsDIYQFnoECBgQAQ&url=https%3A%2F%2Fgithub.com%2Fbrannondorsey%2Fnaive-hashcat%2Freleases%2Fdownload%2Fdata%2Frockyou.txt&usg=AOvVaw3snAERl1mU6Ccr4WFEazBd&opi=89978449">Download rockyou.txt</a>)</p>

<br>

#### *To crack Hashed Passwords just with CyBerGuard run:*

```sh
hash
```

*1.Then you will be prompted to input the type of hash you want to crack, *
*2.And a path to your wordlist of choice*

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Website Brute-Force
- [x] Network Scanner
- [x] Password Hash Crack
- [ ] Malware Creation
- [ ] Wifi-Hacking
    - [ ] Wifi Handshare Capture
    - [ ] Wifi Password Cracking

See the [open issues](https://github.com/CybErGuard2/CybErGuard/issues) for a full list of proposed features (and known issues).

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





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/CybErGuard2/CybErGuard.svg?style=for-the-badge
[contributors-url]: https://github.com/CybErGuard2/CybErGuard/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CybErGuard2/CybErGuard.svg?style=for-the-badge
[forks-url]: https://github.com/CybErGuard2/CybErGuard/network/members
[stars-shield]: https://img.shields.io/github/stars/CybErGuard2/CybErGuard.svg?style=for-the-badge
[stars-url]: https://github.com/CybErGuard2/CybErGuard/stargazers
[issues-shield]: https://img.shields.io/github/issues/CybErGuard2/CybErGuard.svg?style=for-the-badge
[issues-url]: https://github.com/CybErGuard2/CybErGuard/issues
[license-shield]: https://img.shields.io/github/license/CybErGuard2/CybErGuard.svg?style=for-the-badge
[license-url]: https://github.com/CybErGuard2/CybErGuard/blob/master/LICENSE.txt
