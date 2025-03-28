<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
  <h3 align="center">Supervised Classifier for Prostate Cancer Severity</h3>

  <p align="center">
    A supervised learning script using scikit-learn that classifies prostate cancer gene expression data into early and late stage cancer.

  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Script</a>
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
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project



<p align="right">(<a href="#readme-top">back to top</a>)

This project develops a machine learning pipeline to classify prostate cancer gene expression into early and late stages using adaboost. 
The classifier utilizes pathological T score—a post-surgical score reflecting tumor size and spread—as labels, sourced from the TCGA-PRAD Dataset. The goals of building the classifier are:

- Faster, non-invasive alternatives to surgical classification methods
- Enhanced accuracy compared to traditional clinical T score methods

The script also outputs genes the model identifies as the most important features for classification, which could be investigated as potential biomarkers.


</p>

### Built With

- python
- scikit-learn
- [TCGA-PRAD Dataset](https://portal.gdc.cancer.gov/projects/TCGA-PRAD)




<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
* python

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/rboz1/supervised_classifier.git
2. Run the script 
   ```
   python supervised_classifier.py
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
<img width="624" alt="Screenshot 2024-12-21 at 12 41 22 PM" src="https://github.com/user-attachments/assets/83425e54-ec35-4bb9-ac72-7a4b09c1a1a3" />
<img width="624" alt="Screenshot 2024-12-21 at 12 41 48 PM" src="https://github.com/user-attachments/assets/5ad9f0c7-75e5-45d6-a8d8-ab146257e06b" />

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Rachel - rbozadjian@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: www.linkedin.com/in/rachel-bozadjian-203999109

