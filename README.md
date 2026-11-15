<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT TITLE -->
<br />
<div align="center">
  <h3 align="center">hackernet</h3>

  <p align="center">
    A cross-platform mobile client for Hacker News built with Ionic Framework, Angular, and Capacitor.
    <br />
    <em>Academic group project developed at the University of L'Aquila (UNIVAQ).</em>
    <br />
    <br />
    <a href="https://github.com/CarlinoCalogero/univaq-mobile-hackernet/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/CarlinoCalogero/univaq-mobile-hackernet/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

**hackernet** is a mobile application developed as an academic university project at the **University of L'Aquila (UNIVAQ)**.

It provides an intuitive, high-performance, and responsive mobile interface for browsing tech discussions, reading articles, navigating nested comment threads, tracking reading habits, and bookmarking favorite stories for offline access. The application integrates both the official Hacker News Firebase API and the Algolia Search API, offering fast queries, rich filtering, and an offline-first storage architecture powered by SQLite.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Key Features

* **Real-time Story Feeds**: Browse top stories across categories including *Ask HN*, *Show HN*, and *Jobs* with smooth infinite scrolling.
* **Nested Comment Discussions**: Explore hierarchical, collapsible comment trees with deep nesting support and formatted HTML decoding.
* **In-App Article Reader**: Read article text directly or open linked stories inside an embedded view / system browser.
* **Advanced Search & Time Filters**: Filter articles, ask/show posts, jobs, polls, and users with customizable time ranges (last hour, last day, last week, last month) powered by the Algolia API.
* **User Profiles**: View author details, karma scores, bios, submissions, and recent comments.
* **Local Bookmarks & Offline Storage**: Save favorite articles locally with persistent SQLite and Ionic Storage drivers.
* **Personal Reading Analytics**: Built-in metrics tracking daily, monthly, and yearly reading stats, as well as top-read authors and favorite categories.
* **Native Capacitor Features**: Native splash screens, dynamic status bars, and cross-platform native sharing dialogs.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Angular][Angular.io]][Angular-url]
* [![Ionic][Ionic.io]][Ionic-url]
* [![Capacitor][Capacitor.com]][Capacitor-url]
* [![TypeScript][TypeScript.org]][TypeScript-url]
* [![SQLite][SQLite.org]][SQLite-url]
* [![Firebase][Firebase.google.com]][Firebase-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local development environment up and running, follow these steps:

### Prerequisites

* **Node.js** (LTS version recommended) and **npm**
  ```sh
  npm install npm@latest -g
  ```
* **Ionic CLI**
  ```sh
  npm install -g @ionic/cli
  ```
* *(Optional for native Android build)* **Android Studio** and **Android SDK**

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/CarlinoCalogero/univaq-mobile-hackernet.git
   cd univaq-mobile-hackernet
   ```
2. Install NPM dependencies
   ```sh
   npm install
   ```
3. Generate Capacitor assets (icons and splash screens)
   ```sh
   npx capacitor-assets generate
   ```
4. Build web assets and sync native Capacitor dependencies
   ```sh
   npm run build
   npx cap sync
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

### Run in Browser
Run the local development server with live reload:
```sh
npm start
# or
ionic serve
```

### Run on Android
To launch the project in Android Studio or deploy to an emulator / physical device:
```sh
npx cap copy android
npx cap open android
```

### Testing & Linting
Run unit tests with Karma and Jasmine:
```sh
npm test
```

Run ESLint to check code quality:
```sh
npm run lint
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

This project was created as an academic group project at the **University of L'Aquila (UNIVAQ)** and is now archived for portfolio and educational reference. For this reason, **external contributions and pull requests are not accepted**.

However, we proudly showcase the original authors and contributors who designed and developed this project!

### Top contributors:

<a href="https://github.com/CarlinoCalogero/univaq-mobile-hackernet/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=CarlinoCalogero/univaq-mobile-hackernet" alt="contrib.rocks image" />
</a>

* **Calogero Carlino** - [@CarlinoCalogero](https://github.com/CarlinoCalogero)
* **Luca Macera** - [@LucaFraMacera](https://github.com/LucaFraMacera)
* **Manuel Di Cresce (Server-Booster)** - [@Server-Booster](https://github.com/Server-Booster)
* **Piero** - [@Piero9000993](https://github.com/Piero9000993)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

**Calogero Carlino** - [LinkedIn](https://www.linkedin.com/in/calogero-carlino-2a94a33b5/) - carlinocalogero.dev@gmail.com

Project Link: [https://github.com/CarlinoCalogero/univaq-mobile-hackernet](https://github.com/CarlinoCalogero/univaq-mobile-hackernet)

Portfolio: [https://carlinocalogero.github.io](https://carlinocalogero.github.io)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [University of L'Aquila (UNIVAQ)](https://www.univaq.it/)
* [Hacker News Official Firebase API](https://github.com/HackerNews/API)
* [Algolia Hacker News Search API](https://hn.algolia.com/api)
* [Ionic Framework](https://ionicframework.com/)
* [Capacitor](https://capacitorjs.com/)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/CarlinoCalogero/univaq-mobile-hackernet.svg?style=for-the-badge
[contributors-url]: https://github.com/CarlinoCalogero/univaq-mobile-hackernet/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CarlinoCalogero/univaq-mobile-hackernet.svg?style=for-the-badge
[forks-url]: https://github.com/CarlinoCalogero/univaq-mobile-hackernet/network/members
[stars-shield]: https://img.shields.io/github/stars/CarlinoCalogero/univaq-mobile-hackernet.svg?style=for-the-badge
[stars-url]: https://github.com/CarlinoCalogero/univaq-mobile-hackernet/stargazers
[issues-shield]: https://img.shields.io/github/issues/CarlinoCalogero/univaq-mobile-hackernet.svg?style=for-the-badge
[issues-url]: https://github.com/CarlinoCalogero/univaq-mobile-hackernet/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/calogero-carlino-2a94a33b5/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Ionic.io]: https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white
[Ionic-url]: https://ionicframework.com/
[Capacitor.com]: https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white
[Capacitor-url]: https://capacitorjs.com/
[TypeScript.org]: https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[TypeScript-url]: https://www.typescriptlang.org/
[SQLite.org]: https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white
[SQLite-url]: https://www.sqlite.org/
[Firebase.google.com]: https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black
[Firebase-url]: https://firebase.google.com/
