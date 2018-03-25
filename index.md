---
layout: default
---

  <div id="index-banner" class="parallax-container">
    <div class="section no-pad-bot">
      <div class="container">
        <h1 class="header center teal-text text-lighten-2">Kenzo Mutsuda</h1>
        <div class="row center">
          <h5 class="header col s12 light">YouTuber</h5>
        </div>
      </div>
    </div>
    <div class="parallax"><img src="{{site.url}}/assets/images/background1.jpg" alt="Unsplashed background img 1"></div>
  </div>


  <div class="container">
    <div class="section">

      <!--   Icon Section   -->
      <div class="row">
        <div class="col s12 m4">
          <div class="icon-block">
            <h2 class="center brown-text"><i class="material-icons">flash_on</i></h2>
            <h5 class="center">Speeds up development</h5>

            <p class="light">We did most of the heavy lifting for you to provide a default stylings that incorporate our custom components. Additionally, we refined animations and transitions to provide a smoother experience for developers.</p>
          </div>
        </div>

        <div class="col s12 m4">
          <div class="icon-block">
            <h2 class="center brown-text"><i class="material-icons">group</i></h2>
            <h5 class="center">User Experience Focused</h5>

            <p class="light">By utilizing elements and principles of Material Design, we were able to create a framework that incorporates components and animations that provide more feedback to users. Additionally, a single underlying responsive system across all platforms allow for a more unified user experience.</p>
          </div>
        </div>

        <div class="col s12 m4">
          <div class="icon-block">
            <h2 class="center brown-text"><i class="material-icons">settings</i></h2>
            <h5 class="center">Easy to work with</h5>

            <p class="light">We have provided detailed documentation as well as specific code examples to help new users get started. We are also always open to feedback and can answer any questions a user may have about Materialize.</p>
          </div>
        </div>
      </div>

    </div>
  </div>


  <div class="parallax-container valign-wrapper">
    <div class="section no-pad-bot">
      <div class="container">
        <div class="row center">
          <h5 class="header col s12 light">YouTube channel with more than 50K subscribers</h5>
        </div>
      </div>
    </div>
    <div class="parallax"><img src="{{site.url}}/assets/images/background2.jpg" alt="Unsplashed background img 2"></div>
  </div>

  <div class="container">
    <div class="section">

      <div class="row">
     
          <h3><i class="mdi-content-send brown-text"></i></h3>
          <h4>Recent videos</h4>
          
            <div class="col s12 m6 l3">
              <div class="video-container">
                <iframe width="853" height="480" src="//www.youtube.com/embed/FkKkqLc4kD8?rel=0" frameborder="0" allowfullscreen>
                </iframe>
              </div> 
            </div>

            <div class="col s12 m6 l3">
              <div class="video-container">
                <iframe width="853" height="480" src="//www.youtube.com/embed/R5ML-IUw6n4?rel=0" frameborder="0" allowfullscreen>
                </iframe>
              </div> 
            </div>
            
            <div class="col s12 m6 l3">
              <div class="video-container">
                <iframe width="853" height="480" src="//www.youtube.com/embed/LEDlHupVv_I?rel=0" frameborder="0" allowfullscreen>
                </iframe>
              </div> 
            </div>

            <div class="col s12 m6 l3">
              <div class="video-container">
                <iframe width="853" height="480" src="//www.youtube.com/embed/ck8Q3I0NpVI?rel=0" frameborder="0" allowfullscreen>
                </iframe>
              </div> 
            </div>

     
      </div>

    </div>
  </div>


  <div class="parallax-container valign-wrapper">
    <div class="section no-pad-bot">
      <div class="container">
        <div class="row center">
          <h5 class="header col s12 light">More than 500K views every month</h5>
        </div>
      </div>
    </div>
    <div class="parallax"><img src="{{site.url}}/assets/images/background3.jpg" alt="Unsplashed background img 3"></div>
  </div>


  {% assign sponsors = site.data.sponsors %}
  <div class="container">
    <div class="section">
       <div class="row">
          <div class="col s12">
            <h3><i class="mdi-content-send brown-text"></i></h3>
            <h4>Sponsors</h4>
            {% for sponsor in sponsors %}
            <div class="col s12">
              <a href = "{{sponsor.url}}" > {% include sponsor_card.html %} </a>
            </div>
            {% endfor %}
          </div>
        </div>    
      </div>
    </div>