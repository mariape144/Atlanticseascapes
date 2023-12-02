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
