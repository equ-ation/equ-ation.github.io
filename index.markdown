---
layout: base
title: "Equ-ation | Expert R-Shiny Consulting"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index.js
---

<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

# Equ-ation {#title}

## Médiation animale {#subtitle}

#### Accompagnée par une infirmière formée à la médiation animale : [Hélène](/contact) {#sub-subtitle}

<a href="/contact" class="actionbtn">
  <span class="far fa-envelope" aria-hidden="true"></span>
  Me contacter
</a>
{: .actionbtn-out :}

</div>

</div>


<div id="main-sections">

<div id="services-out" class="page-section cut1">
  <div id="services">
    <div class="section-title">Les soins</div>
    <div id="services-list">
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/soins/Complex dashboard.png" />
        <div class="service-text">Building or improving Shiny apps of any complexity</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/soins/Successful completion of project.png" />
        <div class="service-text">Group workshops and private tutoring</div>
      </div>
      <div id="services-break"></div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/soins/Bug tracking.png" />
        <div class="service-text">Code review and optimization of Shiny apps and workflows</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/soins/Work risk-free.png" />
        <div class="service-text">Professional quality R packages and custom solutions</div>
      </div>
    </div>

    <a href="/contact" class="actionbtn">
      <span class="far fa-envelope" aria-hidden="true"></span>
      Me contacter
    </a>
  </div>
</div>

<div class="cut-buffer aboutus-buffer"></div>

<div id="aboutus-out" class="page-section grey-section cut2">
  <div id="aboutus">
    <div class="section-title"> Qui sommes nous ?</div>
    <div id="aboutus-text">
    Équ’ation est une entreprise dédiée à la <b>médiation animale</b>, située dans la métropole lilloise. Fondée par Hélène Stalin, infirmière libérale et passionnée par le monde animal, Équ’ation propose des séances thérapeutiques personnalisées en partenariat avec des animaux soigneusement sélectionnés, comme Ugo, un cheval calme et attentif, et Nala, une lapine douce et expressive. <b>Notre mission</b> est d’améliorer le bien-être physique, psychologique et social de nos bénéficiaires, qu’il s’agisse d’adultes en quête de confiance en soi ou de personnes âgées vivant avec des troubles liés au vieillissement. À travers des interventions bienveillantes et respectueuses, nous créons un espace de reconnexion à soi, dans la sérénité et la nature.
    </div>
  </div>
</div>

<div class="cut-buffer values-buffer"></div>

<div id="values-out" class="page-section cut2">
  <div id="values">
	  <div class="section-title">Nos valeurs</div>
    <div id="values-text">
      Chez Equ-ation, nous croyons que chaque individu a le droit de vivre une vie épanouie et heureuse. Nous croyons que les animaux peuvent jouer un rôle important dans le bien-être des personnes. Nous croyons que la médiation animale est une approche thérapeutique efficace pour les personnes en situation de handicap, les personnes âgées, les enfants et les personnes souffrant de troubles mentaux.
    </div>
    <a href="/contact" class="actionbtn">
      Travaillons ensemble
    </a>
  </div>
</div>

<div id="clients-out" class="page-section cut1">
  <div id="clients">
    <div class="section-title">Les structures</div>
    <div id="clients-subtitle">Les structures dans lesquels nous sommes intervenus</div>
    <div id="client-logos">
      {% for client in site.data.clients %}
        <a class="client-img" href="{{ client.url }}" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="/assets/img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="aboutme-section-out" class="page-section grey-section">
  <div id="aboutme-section">
    <div class="section-title">Quelques infos sur Hélène</div>
	<div id="aboutme-list" markdown="1">
{% for info in site.data.main_info %}
{% if info.icon %}<span class="about-icon fa-fw {{ info.icon }}" aria-hidden="true"></span>{% endif info.icon %}
<span class="about-content">{{ info.content }}</span>
{: .about-text }
{% endfor %}
</div>
  </div>
</div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title">Modo : avec les animaux ...</div><br/>
  </div>
  <a href="/contact" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Me contacter
  </a>
</div>
