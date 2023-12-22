<!-- This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details. -->

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

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
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/tylerjoy/ticketing-app">
    <img src="/public/logo.png" alt="Logo" width="200" height="80">
  </a>

<h3 align="center">Ticketing System</h3>

  <p align="center">
    Ticketing system that tracks work orders to streamline project tracking.
<!--  -->
    <br />
    <a href="https://github.com/tylerjoy/ticketing-app"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/tylerjoy/ticketing-app">View Demo</a>
    ·
    <a href="https://github.com/tylerjoy/ticketing-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/tylerjoy/ticketing-app/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <!-- <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li> -->
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

[![Product Name Screen Shot][product-screenshot]] <!--(https://workfi.up.railway.app/) -->

<!-- <img src="/public/imgs/workfi_search.png" alt="Logo" width="600" height="350"> -->
<!-- <img src="/public/imgs/workfi_results.png" alt="Logo" width="600" height="400"> -->
<!-- <img src="/public/imgs/demo-1.png" alt="Logo" width="600" height="350"> -->

<!-- Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description` -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![Next][Next.js]][Next-url]
- [![React][React.js]][React-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED
## Getting Started

To get a local copy up and running follow these steps.
-->

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm run dev
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/tylerjoy/ticketing-app.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
   <!-- 5. Enter your API keys in `config.js` -->
3. Create a `.env`in root folder and add the following as `key = value`
   ```js
   . MONGODB_URI = your database URI
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

USAGE EXAMPLES

<!-- ## Usage

<!-- _For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

 ROADMAP -->

## Roadmap

- [ ] Add user authentication
- [ ] Add hidden property to work order model so work orders are not deleted (need for reporting and in case user wants to undo deletion)
- [ ] Refactor http requests, initial refresh does not load new data and needs hard refresh

See the [open issues](https://github.com/tylerjoy/ticketing-app/issues) for a full list of proposed features (and known issues).

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
<!-- ## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
 -->

<!-- CONTACT -->

## Contact

Your Name - [@**tylerJS**](https://twitter.com/__tylerJS__) - mrjoy206@gmail.com

Project Link: [https://github.com/tylerjoy/ticketing-app](https://github.com/tylerjoy/ticketing-app)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

<!-- ## Acknowledgments -->

<!-- * []() -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/tylerjoy/workfi.svg?style=for-the-badge
[contributors-url]: https://github.com/tylerjoy/workfi/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/tylerjoy/workfi.svg?style=for-the-badge
[forks-url]: https://github.com/tylerjoy/workfi/network/members
[stars-shield]: https://img.shields.io/github/stars/tylerjoy/workfi.svg?style=for-the-badge
[stars-url]: https://github.com/tylerjoy/workfi/stargazers
[issues-shield]: https://img.shields.io/github/issues/tylerjoy/workfi.svg?style=for-the-badge
[issues-url]: https://github.com/tylerjoy/workfi/issues
[license-shield]: https://img.shields.io/github/license/tylerjoy/workfi.svg?style=for-the-badge
[license-url]: https://github.com/tylerjoy/workfi/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/tyler-joy-m/
[product-screenshot]: /public/product-image.png
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
