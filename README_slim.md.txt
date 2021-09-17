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
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">University of Texas at Austin CS388 Class Final Project</h3>

  <p align="center">
This project explores the application of pretrained
contextual embedding (PCE) models
in comparison to the bidirectional attentive
reader (baseline) implemented by the CS-388
staff. Particularly, I applied DistilBERT (Sanh
et al., 2019) as it is 60% faster to train
and retains 97% of the base BERT performance.
Model comparison was conducted on
the SQuAD 1.1 (Rajpurkar et al., 2016) and
SQuAD adverserial datasets (Jia and Liang,
2017). The HuggingFace implementation of
DistilBERT was utilized, hence I first had to
ensure the SQuAD datasets used match to
that provided by the class staff. Whereas the
baseline model achieved 60.63% and 46.76%
F1 scores on the SQuAD 1.1 and adverserial
SQuAD datasets, respectively, the fine-tuned
DistilBERT model achieved 85.4% and 69.4%,
respectively. Analysis shows that both models
struggle the most with ”why” questions, and
achieve lower F1 scores with increasing answer
lengths.
    <br />
    <a href="https://github.com/aljubrmj/CS388-Final-Project"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/aljubrmj/CS388-Final-Project/issues">Report Bug</a>
    ·
    <a href="https://github.com/aljubrmj/CS388-Final-Project/issues">Request Feature</a>
  </p>
</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Name: [@MJAljubran](https://twitter.com/twitter_handle) - m.j.aljubran@gmail.com

Project Link: [https://github.com/aljubrmj/CS388-Final-Project](https://github.com/aljubrmj/CS388-Final-Project)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/aljubrmj/CS388-Final-Project.svg?style=for-the-badge
[contributors-url]: https://github.com/aljubrmj/CS388-Final-Project/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/aljubrmj/CS388-Final-Project.svg?style=for-the-badge
[forks-url]: https://github.com/aljubrmj/CS388-Final-Project/network/members
[stars-shield]: https://img.shields.io/github/stars/aljubrmj/CS388-Final-Project.svg?style=for-the-badge
[stars-url]: https://github.com/aljubrmj/CS388-Final-Project/stargazers
[issues-shield]: https://img.shields.io/github/issues/aljubrmj/CS388-Final-Project.svg?style=for-the-badge
[issues-url]: https://github.com/aljubrmj/CS388-Final-Project/issues
[license-shield]: https://img.shields.io/github/license/aljubrmj/CS388-Final-Project.svg?style=for-the-badge
[license-url]: https://github.com/aljubrmj/CS388-Final-Project/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/mohammad-jabs/
[product-screenshot]: images/screenshot.png

