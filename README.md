<!-- BACK TO TOP ANCHOR -->
<a id="readme-top"></a>

<!-- LOGO -->
<div align="center">
  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/tomio-studio">
    <img src="assets/logo/LOGO%20TOMIOSTUDIO%20video%20makers.png" alt="Logo" height="80" />
  </a>

  <h1 align="center">Tomio Studio</h1>

  <p align="center">A one-page WordPress site built for Tomio Studio, a Brazilian video production house, to showcase corporate and wedding films and turn visitors into client inquiries.</p>

  <p align="center">// video production · corporate & wedding films</p>

  <br />

  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/tomio-studio"
    ><strong>View it live »</strong></a>
</div>

<br />

<!-- SHIELDS -->
<div align="center">

[![Creator Website][website-shield]][website-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Released][year-shield]][year-url]

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Screenshot][product-screenshot]](https://leonardo-vasconcellos.vercel.app/portfolio/tomio-studio)

<!-- PROJECT INTRO: 260 chars max -->

A one-page WordPress site for Tomio Studio, a Brazilian video production house, showcasing corporate and wedding films through a filterable portfolio, video lightboxes, and a built-in lead-capture contact form.

<!-- END INTRO -->

Tomio Studio is a Brazilian video production company specializing in two service lines: corporate video — commercials, institutional videos, and training content — and Wedding Day Films, cinematic recaps of a couple's wedding day.

This project is the studio's public-facing website: a single-page, parallax-driven WordPress site built on with a custom theme, with a filterable portfolio grid (Corporativo vs. Wedding Day Films), in-page video lightboxes (YouTube embeds via prettyPhoto), a blog used to publish finished client projects as case studies, and a contact section for lead capture. It shipped on WordPress 4.7.1 with a MySQL backend and jQuery-driven interactions (FlexSlider, parallax scrolling, prettyPhoto galleries).

Key features built into the site:

<!-- KEY FEATURES -->
### Key Features

- **Filterable video portfolio** — a one-page parallax site with a filterable reel (Corporativo / Wedding Day Films), letting prospective clients browse by service line and preview embedded reels in-page, shortening the path from discovery to quote request
- **Frictionless lead capture** — a custom contact form with nonce-protected AJAX submission, giving the studio a lead-capture channel directly on the homepage instead of relying on email or social DMs
- **Case-study blog** — category-tagged posts for delivered client work (e.g. Caravana Librelato Joinville, RS Tennis Joinville), turning each finished project into a public case study that doubles as SEO-friendly proof of work for new prospects

This repository is an archival snapshot of the live site — captured via `wget` (see `/rip`) — along with the original theme assets, uploaded media, and a full database export (`db/tomio.sql`), preserved for portfolio reference.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SCREENSHOTS -->
## Screenshots

<div align="center" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;">
  <a href="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%281%29.png"><img src="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%281%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%282%29.png"><img src="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%282%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%283%29.png"><img src="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%283%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%284%29.png"><img src="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%284%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%285%29.png"><img src="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers%20%285%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers.png"><img src="screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->
## Built With

<!-- LANGUAGES -->

**Languages**

|                                                                                                                | Language   | Version |
| ---------------------------------------------------------------------------------------------------------------- | ---------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" /> | JavaScript | ES5     |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" />           | HTML       | 5       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" />             | CSS        | 3       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" />                | PHP        | 5.6     |

<!-- FRAMEWORKS & LIBRARIES -->

**Frameworks & Libraries**

|                                                                                                                  | Framework | Version |
| ------------------------------------------------------------------------------------------------------------------ | --------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-plain.svg" width="20" /> | WordPress | 4.7.1   |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-plain.svg" width="20" />        | jQuery    | 1.12.4  |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="20" />       | MySQL     | 5.7     |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

This project repository is for archive purposes only. No new features or issues are being tracked.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

<a href="https://github.com/llvasconcellos2/tomio-studio/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=llvasconcellos2/tomio-studio" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

[Leonardo Vasconcellos - Website](https://leonardo-vasconcellos.vercel.app/) — [LinkedIn](https://www.linkedin.com/in/llvasconcellos)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[website-shield]: https://img.shields.io/badge/Creator_Website-%E2%86%97-2eba7a?style=for-the-badge
[website-url]: https://leonardo-vasconcellos.vercel.app/
[contributors-shield]: https://img.shields.io/github/contributors/llvasconcellos2/tomio-studio.svg?style=for-the-badge
[contributors-url]: https://github.com/llvasconcellos2/tomio-studio/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/llvasconcellos2/tomio-studio.svg?style=for-the-badge
[forks-url]: https://github.com/llvasconcellos2/tomio-studio/network/members
[issues-shield]: https://img.shields.io/github/issues/llvasconcellos2/tomio-studio.svg?style=for-the-badge
[issues-url]: https://github.com/llvasconcellos2/tomio-studio/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/llvasconcellos
[year-shield]: https://img.shields.io/badge/Released-2014-gray?style=for-the-badge
[year-url]: #
[product-screenshot]: screenshots/TOMIO%20STUDIO%20%C2%BB%20Video%20Makers.png
