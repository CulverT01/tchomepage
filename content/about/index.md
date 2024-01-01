---
layout: layouts/base.njk
eleventyNavigation:
  key: About Me
  order: 3
---

<div class="container fluid">
  <h1 class="col align-self-center">About Me</h1>
  <div class="row justify-content-center">
    <div class="col-6">
      <div class="accordion" id="accordionObject">
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingOne">
              <button class="accordion-button" 
                type="button" 
                data-bs-toggle="collapse" 
                data-bs-target="#collapseOne" 
                aria-expanded="true" 
                aria-controls="collapseOne">
                Me and my skills:
              </button>
            </h2>
            <div id="collapseOne" 
              class="accordion-collapse collapse show" 
              aria-labelledby="headingOne"
              data-bs-parent="#accordionObject">
              <div class="accordion-body">
                  I am a graduate from York St John University with a Degree in Computer Science. <br />
                  I have experience with various programming languages, especially with Python, Java, and HTML. <br />
                  I also have experience with various areas of Computer Science such as Web Development, Databases, Internet of Things, and Software Development. <br />
                  I regularly help out at my local Beaver Scout Troop where I lead sections of meetings and assist the Beaver Scouts when they need help with the activities.
              </div>
            </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingTwo">
            <button class="accordion-button collapsed" 
              type="button" 
              data-bs-toggle="collapse" 
              data-bs-target="#collapseTwo" 
              aria-expanded="false" 
              aria-controls="collapseTwo">
              Likes and Hobbies:
              </button>
              </h2>
              <div id="collapseTwo" 
                class="accordion-collapse collapse" 
                aria-labelledby="headingTwo"
                data-bs-parent="#accordionObject">
                <div class="accordion-body">
                  I like to spend my free time reading japanese light novels and manga. <br />
                  My favourite series that I have read are: Dragon and Ceremony by Ichimei Tsukushi, Kuma Kuma Kuma Bear by Kumanano, Sweetness &amp; Lightning by Gido Amagakure, and CITY by Keiichi Arawi. <br />
                  I also enjoy playing video games which are mostly racing games and the Pokemon series. <br />
                  My favourite games are: Pokemon X, Dirt 5, F1 2019, and Motorsport Manager for the Nintendo Switch. <br />
                  I also play the YuGiOh trading card game and compete in a local weekly tournament.
                </div>
              </div>
        </div>
      </div>
    </div>
  </div>
  <h2 class="col align-self-center">Picture</h2>
  <div class="row justify-content-center">
    {% image "./profile photo 25 percent.jpg", "A headshot of Toby Culverwell, author of this website" %}
  </div>
