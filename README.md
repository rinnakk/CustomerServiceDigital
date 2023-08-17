[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/rinnakk/CustomerServiceDigital">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Customer Service Digital</h3>

  <p align="center">
    An open-source customer service digital solution for your business.
    <br />
    <a href="https://github.com/rinnakk/CustomerServiceDigital"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/rinnakk/CustomerServiceDigital/issues">Report Bug</a>
    ·
    <a href="https://github.com/rinnakk/CustomerServiceDigital/issues">Request Feature</a>
    .
    <a href="https://github.com/rinnakk/CustomerServiceDigital/README.md#contact">End-to-end Service</a>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact Us</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Customer Service Digital is an API solution tailored to provide digital customer service based on OpenAI technologies.

Two custom solutions are currently available:

- Customer service digital for Lead Automation
  A digital customer service representative that can promote customer's products and services, answers user questions, and generate order leads.
- Customer service digital for Services and Ticketing
  A digital customer service representative that can promote customer's products and services, answers user questions, trigger a call-to-action, and submit support tickets.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

Customer service digital solutions are built with these technologies:

- [NodeRed](https://nodered.org/)
- [Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-services/openai-service)
- [Qdrant](https://qdrant.tech/)
- [Azure Table Storage](https://azure.microsoft.com/en-us/products/storage/tables)
- [Azure Application Insights](https://azure.microsoft.com/en-gb/products/monitor)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Prerequisites

To run this program successfully, you need to have these set up:

- Azure OpenAI model instances, see [here](https://oai.azure.com/portal)
  - OpenAI ChatGPT Turbo model (latest)
  - OpenAI Embedding ADA model (latest)
- A running Qdrant database, see [here](https://qdrant.tech/documentation/)
- Azure Table Storage, see [here](https://azure.microsoft.com/en-us/products/storage/tables)
- Azure Application Insights, see [here](https://azure.microsoft.com/en-gb/products/monitor)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/rinnakk/CustomerServiceDigital.git
   ```
2. Go to solution's directory
3. Copy `.env.example` file to `.env` and insert the appropriate value for each key
4. Install NPM packages
   ```sh
   npm install
   ```
5. Run the app
   ```sh
   npm run start
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

rinna can explore the possibilities of providing services for your needs. For more info please contact us:
[Contact rinna](https://rinna.co.jp/inquiry/)

[contributors-shield]: https://img.shields.io/github/contributors/rinnakk/CustomerServiceDigital.svg?style=for-the-badge
[contributors-url]: https://github.com/rinnakk/CustomerServiceDigital/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rinnakk/CustomerServiceDigital.svg?style=for-the-badge
[forks-url]: https://github.com/rinnakk/CustomerServiceDigital/network/members
[stars-shield]: https://img.shields.io/github/stars/rinnakk/CustomerServiceDigital.svg?style=for-the-badge
[stars-url]: https://github.com/rinnakk/CustomerServiceDigital/stargazers
[issues-shield]: https://img.shields.io/github/issues/rinnakk/CustomerServiceDigital.svg?style=for-the-badge
[issues-url]: https://github.com/rinnakk/CustomerServiceDigital/issues
[license-shield]: https://img.shields.io/github/license/rinnakk/CustomerServiceDigital.svg?style=for-the-badge
[license-url]: https://github.com/rinnakk/CustomerServiceDigital/LICENSE
