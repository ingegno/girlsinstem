---
title: Team
layout: default
bodyClass: page-team-list
permalink: /team
---

<!-- Wat is een fablab?-->
<div class="intro">
 <div class="container pt-8 pt-md-1">
    <div class="row">
      <div class="col-12 ">
        <h1>Wat is een FabLab?</h1>
        <p>
         Maar wat is nu eigenlijk een FabLab? Wat zijn de waarden en normen? En wat kun je er nu eigenlijk doen?
        </p>
      </div>
   </div>
  </div>
</div>

<div class="intro-med  container pt-10 pt-md-10">
  <div class="row">
    <div class="col-12 col-md-10">
      <p>
        Een <strong>fab lab</strong> (afkorting van het Engelse fabrication laboratory), is een coöperatieve werkplaats waar uitvinders en ontwikkelaars gebruik kunnen maken van een collectieve infrastructuur. Hier staan onder meer computers, 3D-printers, lasersnijders en frezen.
      </p>
      <p>
        Om de naam fab lab te mogen dragen, moet deze werkplaats voldoen aan het Fab Lab Charter. Het is gebruikelijk op ontwikkelde producten geen patenten te nemen omdat het verdedigen van een patent dat in een Fab Lab is ontwikkeld vrij moeilijk is (er zijn meer dan 1500 labs wereldwijd; hun output te monitoren is onmogelijk voor een Fab Lab uitvinder) en omdat Fab Labs in de geest van open source werken.
      </p>
      <p>
        Bij veel fab labs zoals onder andere bij De Creatieve STEM worden ook opleidingen in de vorm van cursussen en workshops gekoppeld aan de digitale werkplaats. Hierdoor ontstaan langzaamaan totaalconcepten waarin het complete traject van leren, maken, verspreiden en presenteren in de fab labs terug te vinden is.
      <p>
      <h4>Het FabLab Charter</h4>
      <p>
        <strong>Missie:</strong>
        een fablab faciliteert uitvindingen en innovatie door computergestuurde gereedschappen binnen het bereik van individuen te brengen
      </p>
      <p><b>Open toegang:</b> iedereen mag het fablab gebruiken om (bijna) alles te maken (zolang dat niemand schade berokkent); je moet zelf uitvinden hoe je het doet en je moet het fablab delen met anderen
      </p>
      <p><strong>Kennis:</strong> in het fablab leer je van anderen en door het uitvoeren van projecten; je wordt geacht om opgedane kennis weer over te dragen aan anderen, en bij te dragen aan de beschikbare documentatie en gebruiksaanwijzingen
      </p>
      <p><strong>Verantwoordelijkheid:</strong> je bent verantwoordelijk voor:
      </p>
      <ul>
        <li>veiligheid: veilig werken met de gereedschappen en machines</li>
        <li>opruimen: het fablab in een schonere staat verlaten dan dat je het aantrof</li>
        <li>bedrijfsvoering: helpen met voorraadbeheer, onderhouds- en reparatiewerkzaamheden, en het melden van incidenten</li>
        <li>Geheimhouding: alle ontwerpen en processen die ontwikkeld worden in een fablab komen vrij beschikbaar voor persoonlijk gebruik, hoewel intellectueel eigendom naar keuze beschermd kan worden</li>
      </ul>
      <p>
        <strong>Commercie:</strong> commercieel gebruik van het fablab wordt niet uitgesloten, voor zover dat een vrije toegang tot het lab niet in de weg staat; commerciële activiteiten die in het lab ontkiemen worden geacht het fablab op zeker moment te ontgroeien en, eenmaal tot wasdom gekomen, ook tot voordeel te strekken van de uitvinders, het lab en netwerken die tot hun succes leidden.
      </p>
    </div>
  </div>
</div>

<!-- Wat is kets -->
<div class="intro intro-med">
 <div class="container pt-8 pt-md-1">
    <div class="row">
      <div class="col-12 ">
        <h1>Wat is KET's?</h1>
        <p>
          KET's is een project gesponsord door Digital Skill Fund België (DBSF)
        </p>
      </div>
   </div>
  </div>
</div>

<div class="intro-med container pt-10 pt-md-10">
  <div class="row">
    <div class="col-12 col-md-10">
      <p>
        Met Inclusive KETs bouwen we de hefbomen beschikbaar binnen De Creatieve STEM vzw uit om
        (kwetsbare) jongvolwassenen te bereiken, en Key Enabling Technologies (KETs) aan te brengen.
        Dit doen we via faciliteren, opleiden en uitstralen met aandacht voor diversiteit op vlak van rolmodellen
        en gendering of making. Inspiratiebronnen hierbij zijn Fab Academy, Fabricademy, De Waag
        Amsterdam, en Wahallab Nederland. Jongvolwassenen worden aangespoord, begeleid en
        ondersteund in hun zoektocht in het verwerven van kerncompetenties, en dit via oplossen van
        problematieken die hun na aan het hart liggen.
      </p>
    </div>
  </div>
</div>

<!-- WIE ZIJN WIJ -->
<div class="intro intro-med">
 <div class="container pt-8 pt-md-1">
    <div class="row">
      <div class="col-12 ">
        <h1>Wie zijn wij?</h1>
        <p>
          De Creatieve STEM heeft als educatief doel het bevorderen van de ontwikkeling van (talenten van) jongeren. De vereniging wenst een kader te creëren waarbinnen kinderen hun talenten in techniek, wetenschap en talen ontwikkelen. 
        </p>        
      </div>
   </div>
  </div>
</div>

<div class="intro-med container pt-10 pt-md-10">
  <div class="row">
    <div class="col-12 col-md-10">
      <p>
        Met vrije inloopmomenten, cursussen, workshops, speciale vakantieprogramma’s en activiteiten voor scholen en groepen brengt de vereniging dit in de praktijk. De vereniging biedt toegang tot gereedschappen die men thuis niet heeft en tot minder bekende materialen en technieken. Doel is steeds weer het stimuleren van creativiteit, interesse, ontwikkeling en ondernemerschap, met aandacht voor gelijke kansen voor alle kinderen. 
        </p>
    </div>
  </div>
</div>

<div class="container pt-5 pb-5 pt-md-7 pb-md-7">
  <div class="row justify-content-center">
    <div class="col-12">
      <h4 class="title-3 text-dark mb-4">De Creatieve STEM pijlers</h4>
    </div>
    {% for feature in site.data.features %}
    <div class="col-12 col-md-6 col-lg-4 mb-2">
      <div class="feature">
        {% if feature.image %}<div class="feature-image"><img alt="{{ feature.title }} logo" src="{{ feature.image }}" /></div> {% endif %}
        <h2 class="feature-title">{{ feature.title }}</h2>
        <div class="feature-content">{{ feature.description }}</div>
      </div>
    </div>
    {% endfor %}
  </div>
</div>

<div class="intro intro-med">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1>Van wie krijg je les?</h1>
        <p>
          Binnen de FabLab wereld staat kennis delen centraal. Daarom zochten we inhouse, maar ook daarbuiten de beste docenten per passend onderwerp. Hieronder leer je ons allemaal kennen!
        </p>
      </div>
    </div>
  </div>
</div>
<!-- Amy--> 
<div class="intro-med container pb-6">
  <div class="row">
    {% for team in site.team %}
    <div class="col-12 col-md-6 mb-1">
      <div class="team team-summary">
        {% if team.image %}
        <div class="team-image">
          <img
            alt="{{ team.title }} logo"
            class="img-fluid mb-2"
            src="{{site.baseurl}}{{ team.image }}"
          />
        </div>
        {% endif %}
        <div class="team-meta">
          <h2 class="team-name">{{ team.title }}</h2>
          <p class="team-description">{{ team.jobtitle }}</p>
          {% if team.linkedinurl %}
          <a target="_blank" href="{{ team.linkedinurl }}">LinkedIn</a> 
          {% endif %}
        </div>
        <div class="team-content">{{ team.content | markdownify }}</div>
      </div>
    </div>
    {% endfor %}
  </div>
</div>