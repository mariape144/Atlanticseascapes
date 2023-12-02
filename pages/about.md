---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="/objects/agn_smp_4_80a.jpg" %} 

{% include feature/nav-menu.html sections="Atlantic Seascapes;Sobre nosotros" %}

## Sobre Atlantic Seascapes Project

Este archivo digital nace de la preocupación por estudiar nuestro pasado, un pasado compartido por la experiencias caribeñas. Desde siempre, el Caribe, y en su mayor extensión el Atlántico, ha sido un espacio de encuentros de indígenas, cimarrones, piratas, corsarios, marineros, pescadores y esclavos (as). Esta historia compartida vertebró las relaciones intramericanas, así como las de América con Europa, Asia y África. En este espacio de encuentros, el Atlántico fue también el puente para ideas y experiencias. Esta característica, en particular, contribuyó a la difusión de ideas sobre libertad y nación a principios del siglo XIX. Durante las independencias de los países latinoamericanos, la gente de mar fue la protagonista de una historia atlántica. 
A pesar de la gran importancia que tuvo el Caribe, muchos de los documentos necesarios para reconstruir estas experiencias son de difícil acceso hoy en día. Por esa razón, este archivo tiene la intención de poner a disposición documentos que aporten a este objetivo. 

Empezamos esta iniciativa con los documentos de la Secretaría de Marina de Colombia, que entre 1816 y 1830 tenía también documentación de los actuales Venezuela, Colombia, Panamá y Ecuador. Esta documentación se resguarda en el Archivo General de la Nación, Sección República, Fondo Guerra y Marina. Este cuerpo documental no está digitalizado por parte del AGN y las descripciones del catálogo impreso no siempre son útiles para la investigación. 

Por tanto, en aras de poner estos documentos al público, este proyecto ha iniciado con dos facetas distintas pero complementarias. Por un lado, la parte archivística que constó de digitalización y descripción documental, que forma el alma de este proyecto. Dos historiadores de la Universidad de Cartagena han hecho este esfuerzo posible: Meliza Pinzón y Juan Diego Suárez. Por otro lado, el diseño web, que constó del apoyo de [Caribbean Digital Scholarship Collective (CDSC)](https://cdscollective.org/) y de Cornell Library Digital Humanities, en particular de Eliza Betinger e Iliana Burgos, a quienes agradezco infinitamente. Por último, agradezco a la Universidad de Idaho por haber desarrollado este formato de [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv)., que es esqueleto de esta página web. 
## Sobre nosotros


<div style="display: flex; justify-content: space-between;">
  <div style="width: 40%;">
    <img src="/objects/Fotomeliza.jpeg" alt="FotoMeliza" style="display: block; margin: 0 auto;" width="40%">
    <h3 style="text-align: center;">Meliza Pinzón</h3>
    <p style="text-align: left;">Soy historiadora por la Universidad de Cartagena, Colombia. Hago parte del grupo de investigación H-ESOPO (Historia económica, social y política) del Laboratorio de Investigación Histórica en Estudios Coloniales de la misma institución. Me interesa la historia social y económica a través del estudio de las instituciones comerciales del imperio español durante la edad moderna, al analizarlas desde los propios actores, sus redes y estrategias.  
Me entusiasma pertenecer al proyecto Atlantic Seascapes porque facilita el acceso y el análisis a la información de la historia del Caribe y el Atlántico.</p>
  </div>
  <div style="width: 40%;">
     <img src="/objects/FotoJD.jpeg" alt="FotoJD" style="display: block; margin: 0 auto;" width="45%">
    <h3 style="text-align: center;">Juan Diego Suárez</h3>
    <p style="text-align: left;">Mi nombre es Juan Diego Suarez Meza, tengo 22 años y soy estudiante de historia de la Universidad de Cartagena. Mi campo de investigación es la historia ambiental, para mi resulta fascinante estudiar cómo la naturaleza y la sociedad humana chocan y se entrelazan construyendo relaciones históricas que pueden rastrearse y contrastarse. Pienso que Seascapes Project no solo representa un acceso documental digital como otros que ya existen sino que ejemplifica la búsqueda y lucha por construir una historia marítima interdisciplinar, con horizontes que van más allá del sujeto histórico como individuo, preocupándose por sus relaciones y el espacio que habitaba.</p>
</div>

<div class="card mb-3 feature-w-75 mx-auto">
    <h5 class="card-header">Conoce nuestro equipo</h5><div class="card-body">
        <div class="card-text">
        <div style="display: flex; justify-content: space-between;">
  <div style="width: 40%;">
    <img src="/objects/Fotomeliza.jpeg" alt="FotoMeliza" style="display: block; margin: 0 auto;" width="40%">
    <h3 style="text-align: center;">Meliza Pinzón</h3>
    <p style="text-align: left;">Soy historiadora por la Universidad de Cartagena, Colombia. Hago parte del grupo de investigación H-ESOPO (Historia económica, social y política) del Laboratorio de Investigación Histórica en Estudios Coloniales de la misma institución. Me interesa la historia social y económica a través del estudio de las instituciones comerciales del imperio español durante la edad moderna, al analizarlas desde los propios actores, sus redes y estrategias.  
Me entusiasma pertenecer al proyecto Atlantic Seascapes porque facilita el acceso y el análisis a la información de la historia del Caribe y el Atlántico.</p>
  </div>
  <div style="width: 40%;">
     <img src="/objects/FotoJD.jpeg" alt="FotoJD" style="display: block; margin: 0 auto;" width="45%">
    <h3 style="text-align: center;">Juan Diego Suárez</h3>
    <p style="text-align: left;">Mi nombre es Juan Diego Suarez Meza, tengo 22 años y soy estudiante de historia de la Universidad de Cartagena. Mi campo de investigación es la historia ambiental, para mi resulta fascinante estudiar cómo la naturaleza y la sociedad humana chocan y se entrelazan construyendo relaciones históricas que pueden rastrearse y contrastarse. Pienso que Seascapes Project no solo representa un acceso documental digital como otros que ya existen sino que ejemplifica la búsqueda y lucha por construir una historia marítima interdisciplinar, con horizontes que van más allá del sujeto histórico como individuo, preocupándose por sus relaciones y el espacio que habitaba.</p></div>
    </div>
</div>

</div>

<div class="card mb-3{% if include.float %} feature-float-{{ include.float }}{% endif %}{% if include.width %} feature-w-{{ include.width }}{% endif %}{% if include.centered %} mx-auto{% endif %}">
    <div class="row no-gutters">
        <div class="col-md-6">
            {% if include.src1 %}<img class="card-img-top" src="/objects/Fotomeliza.jpeg" alt="{{ include.alt1 | escape }}">{%- endif -%}
        </div>
        <div class="col-md-6">
            {% if include.src2 %}<img class="card-img-top" src="{{ include.src2 }}" alt="{{ include.alt2 | escape }}">{%- endif -%}
        </div>
    </div>
    {% if include.header %}<h5 class="card-header">{{ include.header }}</h5>{%- endif -%}
    <div class="card-body">
        {% if include.title %}<h5 class="card-title">{{ include.title }}</h5>{%- endif -%}
        <div class="card-text">{{ include.text | markdownify }}</div>
    </div>
</div>


<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/visorpdf.md %} 
{% include cb/about_the_about.md %} 

