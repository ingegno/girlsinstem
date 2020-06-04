---
title: Voor partners
layout: default
bodyClass: page-services-list
permalink: /toolkits
---
<!-- Wat betekenen voor jullie werking?-->
<div class="intro">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1>Wat kunnen wij betekenen voor jou werking?</h1>
        <p>
          Dit project draagt zich natuurlijk niet alleen, en daarom hebben wij jou nodig! Ben je een middenvelds organisatie? Kom je in contact met jongvolwassenen tussen de 16 en de 35 die tot een kansengroep behoren? Heb je jongeren in de werking die geschikt zouden kunnen zijn voor deze opleiding? Stuur ze dan zeker door! 
        </p>
      </div>
    </div>
  </div>
</div>

<div class="container pb-6">
  <div class="row">
    {% for service in site.services %}
    <div class="col-12 col-md-4 mb-1">
      <div class="service service-summary">
        <div class="service-content">
          <h2 class="service-title">
            <a href="{{site.baseurl}}{{ service.url }}">{{ service.title }}</a>
          </h2>
          {{ service.content | markdownify | strip_html | truncate: 100 }}
        </div>
      </div>
    </div>
    {% endfor %}
  </div>

<!-- Wie zoeken we?-->
<div class="intro">
 <div class="container pt-6 pt-md-1">
    <div class="row">
      <div class="col-12 ">
        <h1>Wie is onze doelgroep?</h1>
       </div>
   </div>
  </div>
</div>
<div class="intro-med  container pt-10 pt-md-10">
  <div class="row">
    <div class="col-12 col-md-10">
            <h3>Smaakmakers</h3>
                <p>
                    De smaakmaker workshops zijn open voor <b>iedereen</b> en zijn bedoeld om nieuwe technologieën zoals 3D printen en (basis) elektronica naar een brede basis van geïnteresseerden te brengen. <br>
                    Zoek je een activiteit voor jouw organisatie, een teambuilding of heb je gewoon interesse in een van onze workshops, contacteer ons dan zeker. <br>
                    Onder <a href="https://ingegnomakerspace.github.io/inclusievekets/services/smaakmakers/">smaakmakers</a> vind je de volledige lijst van mogelijke workshops terug. 
                </p>
          
            <h3>Open Lab's</h3>
                <p>
                    We helpen partner organisaties bij de opstart van hun eigen Open FabLab. Heb je een vraag, zit je vast, zoek je voor 1 week een machine die wij hebben? Wil je een workshop geven maar weet je niet goed hoe? Dan kunnen we jullie uit de nood helpen. <br>
                    We komen enkele keren helpen tijdens de het project om jullie open lab te begeleiden. Of we geven opleiding op een van de typische fablab machines: lasnijder, 3D printer, CNC frees, vinylsnijder of basis elektronica.
                </p>
          
                <p>
                    De Open Lab momenten zijn momenten waarbij de machines vrij toegankelijk zijn voor iedereen die weet hoe hij of zij ermee moet werken. Deelnemers van het FabZero traject (zie hieronder) worden aangemoedigd om hun aangeleerde kennis te delen met de rest van de community. 
                </p>
          
            <h3>FabZero</h3>
                <p>
                    De FabZero, het voortgezet traject uit de smaakmakers, zoekt deelnemers met het volgende profiel:
                        <ul>
                            <li>De deelnemer behoort tot een kansengroep.</li>
                            <li>De deelnemer is tussen de 16 en 35 jaar</li>
                            <li>De deelnemer kan zich op <strong>woensdagavond</strong> en <strong>een deel van de zaterdag</strong> vrij maken om lessen te volgen of een kleine opdracht te maken. Met andere woorden: je kan je minstens op woensdag en zaterdag vrijmaken om les te volgen of aan projecten te werken.</li> 
                            <li>De deelnemer heeft kennis van computers. Je kan een browser opstarten, weet hoe je met een muis werkt, hoe je een mapje aanmaakt en bestanden versleept. </li>
                            <li>Je spreekt en verstaat voldoende <b>Nederlands</b>.Daarnaast heb je een basis van het Engels. Veel documentatie is in het Engels online te vinden.</li>
                            <li>De deelnemer is <b>gemotiveerd</b></li>
                            <li>De deelnemer heeft affiniteit met technologie, computers en dingen bedenken</li>     
                            <li>De deelnemer kan <b>zelfstandig werken</b></li>                  
                        </ul>
                </p>
            <p>Ken je mensen die naar jou organisatie komen en die misschien interesse hebben in het traject? Download dan <a href="../assets/images/flyers/FabZero2.pdf">hier</a> de flyer! </p>
                
            <h3>FabZero Bootcamp</h3>
                <p>
                    Vanuit verschillende partners kwam de vraag of er ook een mogelijkheid is om een bootcamp te organiseren. Tijdens zo'n bootcamp gaan we in op slechts enkele onderwerpen van het FabZero traject.         
                </p>
          
                <p>
                    In deze bootcamps ga je aan de slag met een select deel van de lessen uit het FabZero pakket. Om zo dicht mogelijk bij de noden te komen van de partnerorganisatie kunnen jullie zelf kiezen welke topics aan bod komen.
                </p>

                <p>
                    Daarnaast kun je ook zelf over de duurtijd van het bootcamp beslissen. Soms gaan deze enkel in de voormiddag door, soms over een volle week met extra werkmomenten in de weken nadien. Of soms gewoon 2 weken “vollenbak” maken, uitvinden en prototypen.
                </p>  
                <p>Ken je mensen die naar jou organisatie komen en die misschien interesse hebben in het traject? Download dan alle flyers.
                <ul>
                    <li><a href="../assets/images/flyers/begeleiders.pdf">Bootcamp voor begeleiders</a></li>
                    <li><a href="../assets/images/flyers/Brussel.pdf">Bootcamp in Brussel</a></li>
                    <li><a href="../assets/images/flyers/Herfstbootcamp.pdf">Bootcamp in de herfstvakantie</a></li>
                    
      
                </ul></p>
      </div>
    </div>
  </div>
</div>
     
    
  <!-- Interesse, contacteer ons-->

<div class="intro-med">
 <div class="container pt-6 pt-md-1">
    <div class="row">
      <div class="col-12 ">
        <h1>Interesse in dit project, maar je hebt nog vragen?</h1>
          <div class="call-box-bottom">
        <a href="mailto:{{ site.data.contact.email }}" class="button">Contacteer ons!</a>   
    </div>
       </div>
   </div>
  </div>
</div>



    <!--Onze partners voorstellen<-->
    
    <div class="intro-med">
    <div class="container pt-5 pb-5 pt-md-7 pb-md-7">
  <div class="row justify-content-center">
      <div class="col-12">
        <h1>Onze partners</h1>
        <p>
          We staat natuurlijk niet alleen in dit project. Hieronder vind je onze partners terug!  
        </p>
          
<div class="container pt-5 pb-5 pt-md-7 pb-md-7">
  <div class="row justify-content-center">
    <div class="col-12">
    </div>
      
      <!-- vzw jong-->
          <div class="col-12 col-md-6 col-lg-4 mb-2">
      <div class="feature">
        
        <h2 class="feature-title">VZW Jong (Gent)</h2>
        <div class="feature-content">
          <p>
              <a href="https://www.vzwjong.be/">
              <img border="0" alt="vzwjong" src="../assets/images/partners/vzwjong.png" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
    <!--Masala -->
    <div class="col-12 col-md-6 col-lg-4 mb-2">
      <div class="feature">
        
        <h2 class="feature-title">Masala (Brugse Poort - Gent)</h2>
        <div class="feature-content"> 
            <p>
              <a href="http://masalagent.be/">
              <img border="0" alt="Masala" src="../assets/images/partners/masala.png" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
      
    <!-- Overkop -->
    <div class="col-12 col-md-6 col-lg-4 mb-2">
      <div class="feature">
        
        <h2 class="feature-title">Overkop (Gent)</h2>
        <div class="feature-content">
          <p>
              <a href="https://overkop.be/huizen/overkop-gent">
              <img border="0" alt="Overkop" src="../assets/images/partners/overkop.png" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
      
       <!-- minus one--> 
      <div class="col-12 col-md-6 col-lg-4 mb-2">
      <div class="feature">
        <h2 class="feature-title">Minus One - Rabot (Gent)</h2>
        <div class="feature-content">
          <p>
              <a href="https://www.minus-one.be/">
              <img border="0" alt="Minus One" src="../assets/images/partners/Minus-One.png" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
      
          <!-- Team Deen--> 
      <div class="col-12 col-md-6 col-lg-4 mb-2">
      <div class="feature">
        <h2 class="feature-title">Team Deen - Gent</h2>
        <div class="feature-content">
              <p>
              <a href="">
              <img border="0" alt="Team Deen" src="../assets/images/partners/teamdeen.jpg" style="float:center;width:200px;height:auto;">
              </a>
            </p>
            </div>
      </div>
    </div>
    
      <!--Digit -->
    <div class="col-12 col-md-6 col-lg-4 mb-2">
    <div class="feature">
     <h2 class="feature-title">Dig-IT (Brussel)</h2>
        <div class="feature-content">
          <p>
              <a href="http://www.dig-it.brussels/">
              <img border="0" alt="Dig-IT" src="../assets/images/partners/digit.jpg" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
         <!--vtssn -->
    <div class="col-12 col-md-6 col-lg-4 mb-2">
    <div class="feature">
     <h2 class="feature-title">WeTech (Sint-Niklaas)</h2>
        <div class="feature-content">
          <p>
              <a href="http://www.wetech.be">
              <img border="0" alt="WeTech" src="../assets/images/partners/sntniklaas.png" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
    <!--habbekrats -->
     <div class="col-12 col-md-6 col-lg-4 mb-2">
    <div class="feature">
     <h2 class="feature-title">Habbekrats (Gent & Wetteren)</h2>
        <div class="feature-content">
          <p>
              <a href="http://www.habbekrats.be/index.php">
              <img border="0" alt="Dig-IT" src="../assets/images/partners/habbekrats.jpg" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
       <!--Bulb werkhuis-->
     <div class="col-12 col-md-6 col-lg-4 mb-2">
    <div class="feature">
     <h2 class="feature-title">Bulb Werkhuis - Muide (Gent)</h2>
        <div class="feature-content">
          <p>
              <a href="https://www.facebook.com/bulb.gent/">
              <img border="0" alt="Dig-IT" src="../assets/images/partners/bulb.jpg" style="float:center;width:200px;height:auto;">
              </a>
            </p>
          </div>
      </div>
    </div>
          
          
    </div>
          </div>
      </div>
        </div>
        </div>
    </div>

        
   