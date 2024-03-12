# E-Commerce Recommendation System using User-Based Collaborative Filtering

<br />
<div align="center">
  <a href="">
    <img src="static/Recommendation System.png">
  </a>
</div>

<p></p>

<!-- TABLE OF CONTENTS -->
<details>
  <p>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#background">Background</a></li>
    <li><a href="#how-to-works">How to Works</a></li>
    <li><a href="#next-step">Next Step</a></li>
    <li><a href="#license">License</a></li>
  </ol>
  </p>
</details>


<p></p>

<!-- ABOUT THE PROJECT -->
## About The Project

Online E-commerce companies use various recommendation engines to recommend a variety of suggestions to customers. By using this recommendation system we can help e-commerce customers who are looking for similar products to purchase, it will be very helpful for them as well as e-commerce companies who are looking to provide the best recommendation system for the website or app.

These E-companies generally use collaborative filtering, which scales to enormous datasets and produces high-quality suggestions. This project builds recommendation system using user-based collaborative filtering

**Note:** This project is still in Jupyter Notebook. The next step is to carry out the packaging and deploying code process.

### Built With

These are list any major frameworks/libraries used to make the project.

* [![Pandas][Pandas]][Pandas-url]
* [![Numpy][Numpy]][Numpy-url]


## Background

In the rapidly evolving world of e-commerce, businesses are constantly seeking innovative ways to engage customers and boost sales. One of the most impactful technological advancements in this domain has been the advent of recommendation systems based on machine learning. These sophisticated algorithms leverage the power of artificial intelligence or machine learning to provide personalized product recommendations to online shoppers, thereby revolutionizing the way shopping online.

## How to Works
User-based collaborative filtering makes recommendations based on user-product interactions in the past. The assumption behind the algorithm is that similar users like similar products.

User-based collaborative filtering algorithm usually has the following steps:
1. Find similar users based on interactions with common items.
2. Identify the items rated high by similar users but have not been exposed to the active user of interest.
3. Calculate the weighted average score for each item.
4. Rank items based on the score and pick the top n items to recommend.

<div align="center">
  <a href="">
    <img src="static/Collaborative Filtering.png" width="400">
  </a>
</div>

## Next Step 
In the next step, we can carry out the packaging and deploying code to be implemented in the production environment.

## License
MIT

<p align="right">(<a href="#automed-forecasting">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Numpy]: https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white
[Numpy-url]: https://numpy.org/
[Pandas]: https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/