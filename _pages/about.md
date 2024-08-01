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
<!-- 
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
    </div> -->


  
  <section class="content-section" id="aboutus">
    <!-- <div class="content-section-heading text-center">
      <h2 class="mdc-typography--headline2 text-center m-0 p-0">About Us</h2>
    </div> -->
    <div class="container-fluid ">
     <div class="row">
       <div class="col-xl-12  col-lg-12 col-sm-12 d-flex align-items-stretch">
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
     <div class="col-xl-12 col-lg-12 col-sm-12 d-flex align-items-stretch">
     We are a multidisciplinary research team comprising of computer scientists, civil engineers, social scientists, urban planners, and public transportation experts dedicated to designing innovative solutions for enhancing public transportation operations. Our focus is on improving availability, reliability, effectiveness, and efficiency. Funded through federal grants and in collaboration with partner agencies such as the Chattanooga Area Regional Transportation Authority (CARTA) and Nashville WeGo, we employ cutting-edge AI approaches to address integrated multi-modal logistics challenges at scale, incorporating both same-day and long-term future trends. A key aspect of our work is the design of models for real-time energy consumption of mixed-vehicle fleets, including electric, hybrid, and diesel vehicles. These models enable us to predict and optimize operations to reduce overall energy impact while maintaining system-wide capacity.
        
        
        <!-- that collaborates with Chattanooga Area Regional Transportation Authority (CARTA) and Nashville WeGo to design
            efficient transit operation algorithms by using artificial intelligence and
            real-time data analysis at scale. This includes reinforcement
            learning, Monte-Carlo tree search, and operations-research based
            optimization for system-wide integrated scheduling and dispatch of
            transit operations. As part of this work, we are also developing
            models to estimate the load factors and real-time energy consumption
            of mixed-vehicle transit fleets and use those models to predict and
            optimize operations in order to lower overall energy impact while
            ensuring that system-wide capacity remains unaffected. -->
      </div></div>
       </div>
  </section>

  
 

 

 <section class="content-section" id="spotlight">
    <div class="content-section-heading text-center">
   <h2 class="mdc-typography--headline2 text-center mb-1 pb-1">R&D Spotlights</h2>
    </div>

<div class="container-fluid mt-4">
     <div class="row p-1 m-1">
     <div class="col-12">
     <h2 class="mdc-typography--headline2 text-center m-2">Microtransit and Paratransit Pilot Operations</h2>
     </div>
    <div class="col-xl-6 col-lg-12 col-sm-12 d-flex align-items-stretch">    
    <!-- <video class="embed-responsive-item" width="100%"   controls="controls" muted="muted">
        <source src="img/SmartTransit.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video> -->
     <div class="embed-responsive embed-responsive-16by9">
     <iframe class="embed-responsive-item" src=" https://www.youtube.com/embed/5-ikHn4g37s"></iframe></div>
    </div>
    <div class="col-xl-6 col-lg-12 col-sm-12 d-flex align-items-stretch">
    {{ "The SmartTransit operations system was recently tested in the Clifton Hills area of Chattanooga. The pilot  was conducted over a span of 27 service days between June and July 2024. On these service days, a vehicle, driver, and booking agent were deployed between 9 am and 3 pm. 
The insights gained from this pilot will be instrumental in refining and expanding microtransit services to better serve the community. Our long-term vision is to provide on-demand microtransit services that act as feeders for high-capacity, fixed-route transit services. Implementing this vision will enable agencies  to provide energy-efficient and equitable transit access in areas with low population density, which are often underserved by existing transit solutions, by combining the energy efficiency of high-capacity transit with the flexibility of microtransit. The  Clifton Hills microtransit pilot served to demonstrate and evaluate our novel technology solutions for on-demand transit. Previously our team tested the system for the CARTA paratransit operations and saw major improvements. Here are the key publications describing the deployment and pilot operations - [IJCAI 2024 Demo](files/paviaIJCAI24demo.pdf), [Paratransit Pilot](files/paviaIJCAI24AISG.pdf)" | markdownify}}
</div>
</div>
</div>

 <div class="container-fluid bg-light mt-4">
     <div class="row p-1 m-1">
     <div class="col-12">
     <h2 class="mdc-typography--headline2 text-center m-2">MicroTransit and ParaTransit Operations Software</h2>
     </div>
    <div class="col-xl-6 col-lg-12 col-sm-12 d-flex align-items-stretch">    
     <div class="embed-responsive embed-responsive-16by9">
     <iframe class="embed-responsive-item" src=" https://www.youtube.com/embed/lF8r0JzHiQc"></iframe></div>    
    </div>
    <div class="col-xl-6 col-lg-12 col-sm-12 d-flex align-items-stretch">
    {{ "The SmartTransit operations system is a modular on-demand public transportation routing system designed to enhance microtransit and paratransit services. It  integrates advanced vehicle routing algorithms into the daily operations of transit agencies, addressing the challenges posed by varying objectives and constraints. This system includes management software for dispatchers and mobile applications for drivers and users. The software has been validated and demonstrated in a southern USA city, in separate microtransit and paratransit pilots, showing significant improvements in operational efficiency, energy efficiency, and cost-effectiveness in both cases. Here are the key publications describing the vehicle routing algorithms related to this work - [Offline Routing With Negotiations @IJCAI 2022](files/sivagnanam2022offline.pdf), [Non-Myopic Online Routing @ICCPS 2022](files/wilbur2022.pdf) [Offline Scalable Routing With Rolling Horizons @AAAI 2023](files/youngseo2023.pdf)" | markdownify  }}
    </div>
    </div>
    </div>

 

<div class="container-fluid bg-light mt-4">
     <div class="row p-1 m-1">
     <div class="col-12">
     <h2 class="mdc-typography--headline2 text-center m-2">Fixed Line Operations with WeGo</h2>
     </div>
    <div class="col-xl-6 col-lg-12 col-sm-12 d-flex align-items-stretch">    
     <div class="embed-responsive embed-responsive-16by9">
     <iframe class="embed-responsive-item" src=" https://www.youtube.com/embed/fbpID2Y5Aao"></iframe></div>
    </div>    
    <div class="col-xl-6 col-lg-12 col-sm-12 d-flex align-items-stretch">
    {{ "Public transit systems provide critical services for large sections of modern communities. Thus, on-time performance and reliable quality of service is important in maintaining ridership. However, disruptions in the form of overcrowding, vehicular failure, and accidents often lead to a degradation in service performance. Current approaches rely heavily on domain expertise by transit agency operators, often resulting in static dispatch locations. We develop AI systems aimed at improving public transit operations by optimizing the stationing and dispatch of substitute buses via data driven models. We also developed Vectura, a dashboard for Nashville's public transportation network. This provides visualization tools to supplement transit operators by providing an information-rich portal for monitoring bus headway and ridership. - [ICCPS 2024 (Best Paper Award)](files/talusan2024ICCPS.pdf), [AAMAS 2024](files/talusan2024AAMAS.pdf)" | markdownify  }}
    </div>
    </div>
    </div>
</section>


 
<!-- <section class="content-section" id="scc">
    <div class="content-section-heading text-center">
   <h2 class="mdc-typography--headline2 text-center mb-1 pb-1">R&D Spotlights</h2>
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
   
  </section> -->

 <section class="content-section " id="updates">
    <div class="container-fluid">
      <div class="content-section-heading text-center">
        <h2 class="mdc-typography--headline2 p-2 text-center m-0 p-0">Publication Spotlight</h2>
      </div>
      <div class="row no-gutters justify-content-center">
        {% for act in site.data.updates limit:4 %}
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
              <p class="mb-0">{{ act.text | markdownify }}</p>
            </div>
          </div>
        </div>
        {% endfor %}
      </div>
      <div class="caption text-center">
      <a class="btn btn-dark js-scroll-trigger"
                href="/publications/">See All Publications</a>   
      </div>
    </div>
  </section>

<!-- <section class="content-section" id="updates">
  <div class="content-section-heading text-justify">
   <h2 class="mdc-typography--headline2 text-center mb-1 pb-1">Publication Spotlight</h2>
    </div>
    <div class="container-fluid">
   <ul class="fa-ul">
  {% for update in site.data.updates limit:3 %}
  <li class="p-0"><span class="fa-li p-0 m-0">
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
-->

     
 

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

  <!-- About -->
  <section class="content-section bg-light text-center" id="team">
    <div class="content-section-heading text-center">
      <h2 class="mdc-typography--headline2 text-center m-0 p-0">Partners</h2>
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
