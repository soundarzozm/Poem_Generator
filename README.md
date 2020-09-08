<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo, twitter_handle, email
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
<p align="left">

  <h1 align="left">Poem Generator with RNN</h1>

  <p align="left">
    Generate poems of different styles by providing a seed text and number of words to be generated.
    <br />
    <a href="https://github.com/soundarzozm/Poem_Generator"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/soundarzozm/Poem_Generator">View Demo</a>
    ·
    <a href="https://github.com/soundarzozm/Poem_Generator/issues">Report Bug</a>
    ·
    <a href="https://github.com/soundarzozm/Poem_Generator/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Data Processing](#process)
  * [Model Definition](#def)
  * [Model Training, and Evaluation](#train)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project
This is a **Deep Learning Natural Language Processing** project using:
1.    [Shakesperian Sonnets](https://github.com/soundarzozm/Poem_Generator/blob/master/sonnets.txt)
2.    [Irish Lyrics](https://github.com/soundarzozm/Poem_Generator/blob/master/irish-lyrics-eof.txt)
<br>
This project consists of *data processing*, *model definition* and *model training and evaluation* using tensorflow. 


### Built With

* [Matplotlib](https://matplotlib.org/)
* [Tensorflow](https://www.tensorflow.org/)
* [NumPy](https://numpy.org/)



<!-- GETTING STARTED -->
## Getting Started

The project consists of three stages:
1. Data Processing
2. Model Definition
3. Model training, and evaluation

The .ipynb (Jupyter Notebook) file contains the three stages of the project.

## Data Processing

Data Processing refers to the analysis, manipulation/transformation of the dataset to obtain a usable form of the data.<br>
This consists of data partitioning, tokenization, padding, etc.

## Model Definition
 
Model definition refers to the process of choosing the models those are best suited for the dataset, along with the initial hyperparameters.

## Model Training, and Evaluation
 
Model training refers to the process of fitting the models to the training data.<br>
Model evaluation refers to the process of evaluating the process of the models using certain appropriate evaluation metrics and tuning the hyperparameters again based on the results.<br>
<br>
It is an iterative process until required performance is obtained. 



<!-- USAGE EXAMPLES -->
## Usage

This model can be used to generate text that is meaningful (Natural Language Processing). This has its various applications such as:<br>
* Auto-completion
* Auto-correction
* Article Generation
* Documentation
* Computer-assisted Coding


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/soundarzozm/Poem_Generator/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Soundar Murugan - [@soundarzozm](https://twitter.com/soundarzozm)<br>
E-Mail - [soundarmurugan91@gmail.com](soundarmurugan91@gmail.com)

Project Link: [https://github.com/soundarzozm/Poem_Generator](https://github.com/soundarzozm/Poem_Generator)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Laurence Moroney](http://www.laurencemoroney.com/) for providing the datasets for public use.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/soundarzozm/Poem_Generator.svg?style=flat-square
[contributors-url]: https://github.com/soundarzozm/Poem_Generator/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/soundarzozm/Poem_Generator.svg?style=flat-square
[forks-url]: https://github.com/soundarzozm/Poem_Generator/network/members
[stars-shield]: https://img.shields.io/github/stars/soundarzozm/Poem_Generator.svg?style=flat-square
[stars-url]: https://github.com/soundarzozm/Poem_Generator/stargazers
[issues-shield]: https://img.shields.io/github/issues/soundarzozm/Poem_Generator.svg?style=flat-square
[issues-url]: https://github.com/soundarzozm/Poem_Generator/issues
[license-shield]: https://img.shields.io/github/license/soundarzozm/Poem_Generator.svg?style=flat-square
[license-url]: https://github.com/soundarzozm/Poem_Generator/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/soundar-murugan
