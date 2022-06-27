![moodle 3](https://img.shields.io/badge/Moodle-3-brightgreen) ![moodle 4beta](https://img.shields.io/badge/Moodle-4beta-brightgreen)

![Licence CC by nc](https://github.com/fxpar/MoodleDesignFr/blob/main/by-nc.eu.svg)


[![Moodle Design](https://i.ytimg.com/vi/RGtL9lzEeq0/hqdefault.jpg)](
https://www.youtube.com/watch?v=RGtL9lzEeq0)



# MoodleDesign FR
*Astuces de Design Moodle avec les composants Bootstrap et FontAwesome déjà inclus dans moodle*

Vous trouverez ci-dessous tous les tutoriaux pour améliorer par simple copier coller le design de vos pages Moodle.
Le fichier téléchargeable "sauvegarde-moodle2..." en haut de cette page contient un cours Moodle avec tous les exemples et les tutos.

* [Entêtes](#entêtes) (jumbotron): exemple et vidéo
* [Liste](#listes): exemple et vidéo
* [Boutons](#boutons-et-liens): vidéo et exemple (primary, outline et danger)
* [Icônes](#icônes): vidéo et exemples
* Cards: simple, avec image, triples
* Alertes (voir [couleurs](#couleurs)): exemples
* [Couleurs](#couleurs): exemple dans les boutons et les alertes
* [Accordéon](#accordéon): exemples et vidéo
* [Popovers](#tooltips-popover): code
* [Onglets](#onglet-tabs): code
* [Carousel](#carousel): code


Astuces pour designer les pages de cours.

# Listes
Aérez vos instructions avec ces listes plus sympathiques

[![Moodle Design Listes](https://i.ytimg.com/vi/gbjehUd36GU/hqdefault.jpg)](
https://www.youtube.com/watch?v=gbjehUd36GU)

<details>
  <summary> <b>Dépliez pour voir les liens et le code</b> </summary>

* Bootstrap list groups: https://getbootstrap.com/docs/4.0/components/list-group/

````    
     <ul class="list-group">
      <li class="list-group-item active">Cras justo odio</li>
      <li class="list-group-item">Dapibus ac facilisis in</li>
      <li class="list-group-item">Morbi leo risus</li>
      <li class="list-group-item">Porta ac consectetur ac</li>
      <li class="list-group-item">Vestibulum at eros</li>
     </ul>
````

* Bootstrap Cards Lists: https://getbootstrap.com/docs/4.0/components/card/#list-groups

````
    <div class="card" style="width: 18rem;">
        <div class="card-header">
          Featured
        </div>
        <ul class="list-group list-group-flush">
          <li class="list-group-item">Cras justo odio</li>
          <li class="list-group-item">Dapibus ac facilisis in</li>
          <li class="list-group-item">Vestibulum at eros</li>
        </ul>
    </div>
    
````
  
</details>

# Entêtes

Affichez clairement le thème d'une séance, et énoncez les objectifs en mode grand format.


[![Moodle Bootstrap Entête Jumbotron](https://i.ytimg.com/vi/akNsaCv8k4c/hqdefault.jpg)](
https://www.youtube.com/watch?v=akNsaCv8k4c)

<details>
  <summary><b>Dépliez pour voir les liens et le code</b></summary>
  
* Bootstrap 4 Entête: Le magnifique "Jumbotron" : https://getbootstrap.com/docs/4.0/components/jumbotron/
  
````
    <div class="jumbotron">
      <h1 class="display-4">Hello, world!</h1>
      <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
      <hr class="my-4">
      <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
      <p class="lead">
        <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
      </p>
    </div>
````
  
  </details>

# Boutons et Liens

Réutilisez les activités... sans avoir à les déplacer. Une bonne façon de rappeler les étapes d'une préparation aux étudiants.

[![Moodle Design Boutons et Liens](https://i.ytimg.com/vi/3TFrNehPdiw/hqdefault.jpg)](
https://www.youtube.com/watch?v=3TFrNehPdiw)

<details>
  <summary><b>Dépliez pour voir les liens et le code</b></summary>
  
* Bootstrap Boutons: https://getbootstrap.com/docs/4.0/components/buttons/

Officiellement, on utiliserait des boutons.
  
````
    <button type="button" class="btn btn-primary">Primary</button>
    <button type="button" class="btn btn-outline-secondary">Secondary</button>
    <button type="button" class="btn btn-success">Success</button>
````

Toutefois je préfère utiliser des liens:
    
````
    <a href="#" type="button" class="btn btn-primary">Primary</a>
    <a href="#" type="button" class="btn btn-outline-secondary">Secondary</a>
    <a href="#" type="button" class="btn btn-success">Success</a>
````
  </details>

# Icônes

8% de la population a du mal à discerner les couleurs... Heureusement, vous pouvez apporter un indice visuel à vos boutons, et à vos activités.

Et puis c'est tellement plus parlant 😁

[![Moodle Icônes FontAwesome](https://i.ytimg.com/vi/d1UE_9AcWd0/hqdefault.jpg)](
https://www.youtube.com/watch?v=d1UE_9AcWd0)



<details>
  <summary><b>Dépliez pour voir les liens et le code</b></summary>
  
* FontAwesome 4: https://fontawesome.com/v4/icons/
  
``<i class="fa fa-address-book" aria-hidden="true"></i>``
  Pour des raisons d'accessibilité le code suivant serait toutefois préférable:
``<span class="fa fa-address-book" aria-hidden="true"></span>``
  
  </details>

# Couleurs
Excellent pour créer des contenus en harmonie avec le reste du site de votre école.

[![Moodle Couleurs](https://i.ytimg.com/vi/vcQ4wdHebsM/hqdefault.jpg)](
https://www.youtube.com/watch?v=vcQ4wdHebsM)

*Rappelez à votre admin d'ajouter ces couleurs au fichier css de l'appli mobile.

# Accordéon

Vos étudiants se sentent parfois submergés par une longue liste d'actions à réaliser ?
Vous aimeriez qu'ils ou elles puissent afficher progressivement les ressources que vous leur avez préparé?
Voici l'accordéon, déjà inclus dans moodle, accessible par un simple copier coller 😍


[![Moodle Design Accordéon](https://i.ytimg.com/vi/LjNU3fgSn3s/hqdefault.jpg)](
https://www.youtube.com/watch?v=LjNU3fgSn3s)


# Tooltips Popover

Vous voulez ajouter des étiquettes pour expliquer à quoi sert un bouton. Normalement, les tooltips sont les outils qu'ils vous faut. Malheureusement, cela n'a pas l'air de fonctionner dans Moodle 3. PAr contre, l'autre outil qui fait cela est déjà inclus dans Moodle: ce sont les popovers qui affiche l'aide sur les point d'interrogation dans les les options.

* Tooltips: https://getbootstrap.com/docs/4.0/components/tooltips/
* Popovers: https://getbootstrap.com/docs/4.0/components/popovers/

Notez que dans l'exemple suivant, j'ai utilisé un "badge" au lieu d'un bouton, et j'ai choisi de le déclencher en passant la souris au dessus ("hover"). Enfin, j'ai mis du html dans mon étiquette avec la balise "b".

<details>
  <summary><b>Dépliez pour voir les liens et le code</b></summary>
  
````  
<span class="badge badge-dark" role="button" data-container="body" data-toggle="popover" data-placement="top" data-html="true" tabindex="0" data-trigger="hover" data-original-title="" title="" data-content="<b>Durée totale</b> du parcours">⏱️ 6h</span>
````
</details>



# Onglet (Tabs)

Pour afficher plusieurs options d'un même thème, les onglets (comme un classeur) s'avèrent très utiles.


<details>
  <summary><b>Dépliez pour voir les liens et le code</b></summary>

Tabs: https://getbootstrap.com/docs/4.0/components/navs/#tabs
  
````  
<ul class="nav nav-tabs" id="myTab" role="tablist">
  <li class="nav-item">
    <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">Home</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">Profile</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="contact-tab" data-toggle="tab" href="#contact" role="tab" aria-controls="contact" aria-selected="false">Contact</a>
  </li>
</ul>
<div class="tab-content" id="myTabContent">
  <div class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">...</div>
  <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">...</div>
  <div class="tab-pane fade" id="contact" role="tabpanel" aria-labelledby="contact-tab">...</div>
</div>
````
</details>


# Carousel

Faites tourner les images, les questions de quiz, ou permettez l'approfondissement en balayant l'écran avec le carousel.



<details>
  <summary><b>Dépliez pour voir les liens et le code</b></summary>

Carousel: https://getbootstrap.com/docs/4.0/components/carousel/

  
```` 
<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="..." alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="..." alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="..." alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

````
</details>

# Changer d'éditeur

Si votre école utilise un autre éditeur pour les étiquettes, voici comment en changer:
Cliquez sur votre nom ou votre image > préférences > préférence d'éditeur

[![Moodle Design Accordéon](https://i.ytimg.com/vi/5vnGpaflLNs/hqdefault.jpg)](
https://www.youtube.com/watch?v=5vnGpaflLNs)

# Télécharger les exemples
Instructrices et instructeur, vous pouvez télécharger une page moodle avec les exemples.

C'est le fichier "sauvegarde-moodle2...mbz" situé en haut de cette page.

##  la version anglaise
You don't understand french? no pb, here are the english versions
https://github.com/fxpar/MoodleDesignEn



# Actualité Pédagogique
Retrouvez tout le fil des mes lectures en pédagogie sur le site : https://www.fxparlant.net/tag/pedagogie/

