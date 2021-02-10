---
layout: default
title: Home
sitemap:
 changefreq: 'weekly'
 priority: 0.7
---

<section class="py-5 text-center jumbotron" id="jumbotron">
  <div class="row py-lg-5">
    <div class="col-lg-6 col-md-8 mx-auto mt-4 textcontainer">
      <h1 class="fw-light"><b>James Richard Robbins</b></h1>
      <p class="fw-light"><b>Marine vertebrate biologist</b></p>
    </div>
  </div>
</section>

<!-- Show last news item (if it's less than a week old) -->
{% include newsitems.html limit="1" %}

<div class="album py-2 bg-light">
  <div class="container">

    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-j g-3">
       
      <div class="col">
        <div class="card shadow-sm">
          <div class="bg-image">
            <a href="/about.html">
              <img src="https://lh3.googleusercontent.com/pw/ACtC-3cIxKLFNNJ11H_VAVEiDYVD2xteHf2EskJVpmRWgIkjg50tzNybVPegQA4Jgy7xbG9tPS0guBXi44SPUSkYcIHkpJEMQJdJhjp89e9h2Eg08WZBiR2udjvA7OHoEMU51JWQm8WF74o7hZo3mTj2XbdGTQ=w640-no?authuser=0" class="img-fluid" alt="More About Me"/>
            <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
              <div class="d-flex justify-content-center align-items-center h-100">
                <p class="text-white mb-0">More About Me</p>
              </div>
            </div>
            </a>
          </div>          

          <div class="card-body">
            <p class="card-text">A little bit more about myself, my adventures, and what's coming up next.</p>
          </div>
        </div>
      </div>
     
      <div class="col">
        <div class="card shadow-sm">
          <div class="bg-image">
            <a href="/writing.html">
              <img src="https://lh3.googleusercontent.com/pw/ACtC-3fhDtCDmv0BGP5yxhcqHAvHmX_hSH1-YvHttXMmzdFhDP8PyrFp7tFsdVX6aBa2gJYvLOlXFD89WFuYc7Fc0rOKo-be5BKkWMVbh4KsDfHPLx4chiRQtvkeA_af0Cz5m6J75VpaaCZq4e_wPdsXrNoAHA=w640-no?authuser=0" class="img-fluid" alt="Research and Publications"/>
            <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
              <div class="d-flex justify-content-center align-items-center h-100">
                <p class="text-white mb-0">Research and Publications</p>
              </div>
            </div>
            </a>
          </div>          

          <div class="card-body">
            <p class="card-text">A summary of some of my professional articles.</p>
          </div>
        </div>
      </div>

    </div>
  </div>
</div>

