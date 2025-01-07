<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--

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
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#Contributing">Contributing</a></li>
    <li><a href="#Contact">Contact</a></li>
    <li><a href="#next-steps">Next Steps</a></li>
    <li><a href="#Additional Resources">Additional Resources</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


This project is a basic language model designed to explore the concepts of transformers and multi-headed attention mechanisms. It follows the principles outlined in the paper "Attention is All You Need." The model consists of approximately 10.8 million parameters and was trained on Shakespearian text. While significantly smaller than large language models (LLMs) like GPT, the primary goal was to gain a deeper understanding of how LLMs work by building one from scratch.

Running the model on a standard PC can take 6–12 hours or more, depending on your system's architecture. However, if you have access to a GPU, the runtime reduces significantly to about 15 minutes.

### Results: 

<table border="1">
  <thead>
    <tr>
      <th>Step</th>
      <th>Train Loss</th>
      <th>Validation Loss</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>4.2221</td>
      <td>4.2306</td>
    </tr>
    <tr>
      <td>500</td>
      <td>1.7442</td>
      <td>1.8909</td>
    </tr>
    <tr>
      <td>1000</td>
      <td>1.4035</td>
      <td>1.6207</td>
    </tr>
    <tr>
      <td>1500</td>
      <td>1.2687</td>
      <td>1.5358</td>
    </tr>
    <tr>
      <td>2000</td>
      <td>1.1900</td>
      <td>1.5043</td>
    </tr>
    <tr>
      <td>2500</td>
      <td>1.1270</td>
      <td>1.4826</td>
    </tr>
    <tr>
      <td>3000</td>
      <td>1.0698</td>
      <td>1.4787</td>
    </tr>
    <tr>
      <td>3500</td>
      <td>1.0199</td>
      <td>1.5050</td>
    </tr>
    <tr>
      <td>4000</td>
      <td>0.9628</td>
      <td>1.5148</td>
    </tr>
    <tr>
      <td>4500</td>
      <td>0.9119</td>
      <td>1.5441</td>
    </tr>
    <tr>
      <td>4999</td>
      <td>0.8580</td>
      <td>1.5901</td>
    </tr>
  </tbody>
</table>

### 500 Token Output

Our fair, or fair mother stain past them honest Upon my wintous, grow, kneel day:
Be not to grant, if supple her friends, And play with this morn ere shall be practised.
GLOUCESTER:
Think, must not I do but do my sweet word.
Servant:
Had I they dropp'd here.
QUEEN ELIZABETH:
My liege; for I love none like apUful the stabble They denied the steuntations, And now these patrons wildle whate'er graced
And handly bear it. Why, ho! What, art your cozn hand That we should to Mantague'?
Or am I a pro

As expected, the model's output is not very meaningful. This is partly due to the nature of the input data used for predictions, but it is primarily because this is a smaller model. Its limited capacity affects its ability to generate coherent results.

#### A longer output can be found in more.txt. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

For this project I really did not have to use much, as I only used the torch library. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Make sure you have the above packages installed. 
   ```sh
   pip install torch
   ```
2. Clone the repo
   ```sh
   git clone https://github.com/rohanvc/Basic-Language-Model-with-Multi-Headed-Attention-Blocks.git
   ```
3. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
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


<!-- CONTACT -->
## Contact

Rohan Chaturvedula - [Linkedin](https://www.linkedin.com/in/rohan-chaturvedula/) - rchat10@gmail.com


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Next Steps

- [ ] Pretrain this model on a larger dataset, then fine-tune it with Shakespeare
- [ ] Build GPT-2 from scratch
- [ ] Fine-tune models for specific real-world applications

## Additonal Resources

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY)
* [Attention is All You Need](https://arxiv.org/abs/1706.03762)
* [Neural Networks Learning Series](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/Stock.webp
[data-splits]: images/dataSplits.png
[training-results]: images/TrainingResults.png
[validation-results]: images/ValidationResults.png
[overall-results]: images/OverallResults.png
[recursive-results]: images/RecursiveResults.png

