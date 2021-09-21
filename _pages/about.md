---
permalink: /
title: "Smart Transit Systems"
excerpt: "About SmartTransit.ai"
author_profile: true
layout: single
redirect_from:
- /about/
- /about.html
---

  <div class="containerh-100 d-flex justify-content-center">
    <div class="row">
      <div class="col-lg-12 col-xl-11 col-sm-12 mx-auto">
        <div id="carouselData" class="carousel slide carousel-fade"
          data-ride="carousel" data-interval=8000>
          <div class="carousel-inner">
            {% for carousel in site.data.carousels %}
            {% if carousel.active %}
            <div class="carousel-item active align-items-center">
              {% else %}
              <div class="carousel-item align-items-center">
                {% endif %}
                {% if carousel.video %}
                <video id="videoBanner" width="100%" loading="lazy" class="d-block w-100 p-0 m-0" autoplay
                  loop muted>
                  <source src="{{ carousel.video }}" type="video/mp4" />
                </video>
                {% else %}
                <img class="d-block w-100 p-0 m-0" loading="lazy" src="{{ carousel.image }}"
                  alt="Slide">
                {% endif %}
                 {% if carousel.text %}
                 <div class="carousel-caption d-none d-md-block">
                 <p> {{ carousel.text }} </p>
                 </div>
                 {% endif %}
              </div>
              {% endfor %}
            </div>
            <a class="carousel-control-prev" href="#carouselData" role="button"
              data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselData" role="button"
              data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
      </div>
    </div>


  
  <section class="content-section" id="aboutus">
    <div class="content-section-heading text-center">
      <h2 class="mdc-typography--headline2 text-center m-0 p-0">About Us</h2>
    </div>
    <div class="container-fluid ">
        We are a research team that collaborates with Chattanooga Area Regional Transportation Authority (CARTA) and Nashville WeGo to design
            efficient transit operation algorithms by using artificial intelligence and
            real-time data analysis at scale. This includes reinforcement
            learning, Monte-Carlo tree search, and operations-research based
            optimization for system-wide integrated scheduling and dispatch of
            transit operations. As part of this work, we are also developing
            models to estimate the load factors and real-time energy consumption
            of mixed-vehicle transit fleets and use those models to predict and
            optimize operations in order to lower overall energy impact while
            ensuring that system-wide capacity remains unaffected.
      </div>
  </section>

  <section class="content-section" id="study">
      <div class="content-section-heading text-center">
      <h2 class="mdc-typography--headline2 text-center m-0 p-0">Transit Needs and Expectation Study</h2>
    </div>
  <div class="container-fluid p-1 m-1">
  <div class="row p-0 m-0">
   <div class="col-sm-6 col-lg-4 col-xl-3 p-0 ml-xl-3 my-auto mx-auto">
   <img class="m-0 p-0 d-inline-flex" src="img/community.png" alt="community image">   
   </div>  
    <div class="col-lg-7 col-xl-8 p-0 m-0 mx-auto">
   <p class="card-text text-justify   mr-4">
   We are conducting a research study to understand the community challenges and expectation around public transit in Chattanooga, TN. The project is looking for Chattanooga residents, 18 and older, to join us in paid focus group sessions to discuss how community infrastructure supports, or does not support interests and concerns that are most important to you.</p>
    <p class="card-text text-justify   mr-4">
   Participants will receive gift cards for their time and help on the project. The conversations will help us better understand the needs and expectations and challenges of the community. Since the conversation will be virtual, we  invite interested participants who have a reliable internet connection to get in touch with us at Mobility.Chattanooga@gmail.com.
   </p>
 </div> 
  </div>  
  </div>  
  </section>

  <section class="content-section" id="updates">
  <div class="content-section-heading text-justify">
   <h2 class="mdc-typography--headline2 text-center mb-1 pb-1">News and Updates</h2>
    </div>
    <div class="container-fluid">
   <ul class="fa-ul">
  {% for update in site.data.updates %}
  <li><span class="fa-li">
  {% if update.presentation %}
    <i class="fas fa-file-powerpoint">
    {% else %}
  <i class="fas fa-bookmark">
    {% endif %}
  </i></span>{{ update.text | markdownify }}</li>
  {% if update.active %}
  {% endif %}
  {% endfor %}
  </ul>
   </div>
   </section>

  <!-- Research Areas -->
  {% assign sortedresearchareas = site.researchareas | sort: 'sequence' %}
  <section class="content-section" id="research">
    <div class="content-section-heading text-center">
      <h2 class="mdc-typography--headline2 p-2 text-center m-0 p-0">Focus
        Areas</h2>
    </div>
    <div class="row">
      {% for area in sortedresearchareas %}
      <div class="col-xl-4 d-flex align-items-stretch">
        <div class="card bg-light  border-1 m-1 ">
          <h5 class="card-header text-center">{{ area.name }}</h5>
          <div class="card-body d-flex flex-column text-card-justify">
            {{ area.content | markdownify }}
            {% if area.learnmore == blank and area.learnmore == nil %}
            <div class="text-center"><a class="align-self-end btn btn-dark  js-scroll-trigger"
                href="#research">Learn More</a></div>
            {% else %}
            <div class="text-center align-bottom"><a class="align-self-end btn btn-dark  js-scroll-trigger"
                href="{{ area.learnmore }}">Learn More</a></div>
            {% endif %}
          </div>
          <div class="card-footer  text-center">Funding: {{
            area.funding }}</div>
        </div>
      </div>
      {% endfor %}
    </div>
  </section>

 

 
  <section class="content-section" id="scc">
    <div class="content-section-heading text-center">
   <h2 class="mdc-typography--headline2 text-center mb-1 pb-1">Smart and Connected Communities</h2>
    </div>
    <div class="container-fluid p-1 m-1">
      <div class="row p-0 m-0">
        <div class="col-sm-6 col-lg-4 col-xl-3 p-0 ml-xl-3 my-auto mx-auto">
            <img class="m-0 p-0 d-inline-flex" src="img/smartcities.png" alt="scopelab image">   
        </div>
        <div class="col-lg-7 col-xl-8 p-0 m-0 mx-auto">
   <p class="card-text text-justify   mr-4"> This research effort is part of the broader research that is being conducted in the area of smart and connected communities (SCC). As a research area, SCC is multidisciplinary and lies at the intersection of cyber-physical systems, data science, and social sciences. This research area is enabled by the rapid and transformational changes driven by innovations in smart sensors, such as cameras and air quality monitors, which are now embedded in almost
every physical device and system we use, from watches and smartphones to automobiles,
homes, roads, and workplaces. Coupled with emerging new modes of networking, new
algorithms for data analytics, and new paradigms of distributed computing like fog computing,
these sensors create an “Internet of Things” (IoT) that provide endless opportunities for
innovation and improving the quality of life, such as improved transportation with reduced
congestion and more efficient use of energy and water. The effect of these innovations can be seen in a number of diverse domains, such as transportation, energy, emergency response, and health care, including the transit-related efforts of our team.
Read more at the <a href="https://www.nsf.gov/cise/scc/">National Science Foundation page.</a> </p>
        </div>
      </div>
    </div>
    <!-- <div class="text-center">    
          <a class="btn btn-dark  js-scroll-trigger" href="#research">Research Areas</a></div> -->
  </section>


  <!-- About -->
  <section class="content-section bg-light text-center" id="team">
    <div class="content-section-heading text-center">
      <h2 class="mdc-typography--headline2 text-center m-0 p-0">Partnering Organizations</h2>
    </div>
    <div class="container-fluid p-0 m-0 mx-auto">
      <div class="row p-1 m-1">
        <div class="col-lg-4 col-xl-3 p-0 ml-3 my-auto mx-auto">
            <a href="https://www.isis.vanderbilt.edu/"><img class="m-0 p-0 d-inline-flex" width="30%" src="img/logos/isis.png" alt="isis vu image"> </a>    
          <a href="https://www.vanderbilt.edu/"><img class="m-0 p-0 mr-2 d-inline-flex" width="30%" src="img/logos/vu.jpg" alt="vu image">    </a>  
          <a href="https://www.uh.edu/"><img class="m-0 p-0  mr-2 d-inline-flex" width="30%" src="img/logos/uh.png" alt="uh image">  </a>    
            <a href="https://www.pnnl.gov/"> <img class="m-0 p-0  mr-2 d-inline-flex" width="25%" src="img/logos/pnnl.png" alt="pnnl image">  </a> 
          <a href="https://www.cornell.edu/"><img class="m-0 p-0 mr-2 d-inline-flex" width="30%" src="img/logos/cornell.gif" alt="cornell image">  </a>    
         <a href="https://www.washington.edu/about/?utm_source=whitebar&utm_medium=click&utm_campaign=campuses&utm_term=seattle"> <img class="m-0 p-0  mr-2 d-inline-flex " width="30%" src="img/logos/uw.png" alt="uw image">   </a>   
          <a href="https://www.utc.edu/"><img class="m-0 p-0  mr-2 d-inline-flex " width="20%" src="img/logos/utc.png" alt="utc image">   </a> 
         <a href="https://new.siemens.com/us/en/company/siemens-in-the-usa/princeton.html"> <img class="m-0 p-0  mr-2 d-inline-flex" width="25%" src="img/logos/siemens.jpg" alt="siemens image">    </a>     
           <a href="http://www.carta-bus.org/">   <img class="m-0 p-0 mr-2 d-inline-flex" width="30%" src="img/logos/carta.jpeg" alt="carta image">  </a> 
        </div>
        <div class="col-lg-7 col-xl-8 p-0 m-0 mx-auto text-card-justify">
          {% for node in site.info %}
          {{ node.content| markdownify }}
          {% endfor %}
        </div>
      </div>
    </div>
    <!-- <div class="text-center">    
          <a class="btn btn-dark  js-scroll-trigger" href="#research">Research Areas</a></div> -->
  </section>

  <!-- Portfolio -->
  {% assign sortedactivities = site.activities | sort: 'sequence' %}
  <section class="content-section " id="activities">
    <div class="container-fluid">
      <div class="content-section-heading text-center">
        <h2 class="mdc-typography--headline2 p-2 text-center m-0 p-0">Selected
          Articles and Talks</h2>
      </div>
      <div class="row no-gutters justify-content-center">
        {% for act in sortedactivities %}
        <div class="col-sm-10 col-lg-5 col-xl-5 p-lg-1 m-lg-1">
          {% if act.link != blank or act.link != nil %}
          <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item" src="{{ act.link }}"></iframe>
            {% if act.learnmore != blank or act.learnmore != nil %}
            <div class="text-center"><a class="btn btn-dark js-scroll-trigger"
                href="{{ act.learnmore }}">Learn More</a></div>
            {% endif %}
          </div>
          {% endif %}
          <div class="caption text-center">
            <div class="caption-content">
              <div class="h2">{{ act.caption }}</div>
              <p class="mb-0">{{ act.text }}</p>
            </div>
          </div>
        </div>
        {% endfor %}
      </div>
      <div class="caption text-center">
      <a class="btn btn-dark js-scroll-trigger"
                href="/talks/">Learn More</a>   
      </div>
    </div>
  </section>

{% assign allpeople = site.data.people | sort: 'sequence' %}
<section class="content-section " id="people">
    <div class="container-fluid">
      <div class="content-section-heading text-center">
        <h2 class="mdc-typography--headline2 p-2 text-center m-0 p-0">People</h2>
      </div>
      <div class="row no-gutters justify-content-center">
        {% for act in allpeople %}        
<div class="card  bg-light border-0 m-3 ">
  <img src="{{ act.picture }}" class="card-img-top border-0 m-0 p-0 rounded float-left fit-image" alt="...">
  {% if act.link != blank or act.link != nil %}
   <p class="card-text text-center border-0 m-0 p-0"><a class="js-scroll-trigger"
                href="{{ act.link }}">{{act.name}} </a></p>
  {% else %}
  <p class="card-text text-center border-0 m-0 p-0">{{act.name}}</p>
  {% endif %}
  <p class="card-text text-center border-0 m-0 p-0">{{act.role}}</p> 
  <p class="card-text text-center border-0 m-0 p-0">{{act.org}}</p> 
</div>  
        {% endfor %}
      </div>
    </div>
  </section>


  <!-- Map -->
  <div id="contact" class="map">
    <iframe
      src="https://www.google.com/maps/d/embed?mid=1ZnAR4JdHNF5K3rW9cICXqBGuvwmchIy9&hl=en"
      width="100vw"></iframe>
  </div>
