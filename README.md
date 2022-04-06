![moodle 3](https://img.shields.io/badge/Moodle-3-brightgreen) ![moodle 4beta](https://img.shields.io/badge/Moodle-4beta-brightgreen)

![Licence CC by nc](https://github.com/fxpar/MoodleDesignFr/blob/main/by-nc.eu.svg)

# MoodleDesign FR
*Astuces de Design Moodle avec les composants Bootstrap et FontAwesome déjà inclus dans moodle*

Vous trouverez ci-dessous tous les tutoriaux pour améliorer par simple copier coller le design de vos pages Moodle.
Le fichier téléchargeable "sauvegarde-moodle2..." en haut de cette page contient un cours Moodle avec tous les exemples et les tutos.

* Entêtes (jumbotron): exemple et vidéo
* Liste: exemple et vidéo
* Bouton: vidéo et exemple (primary, outline et danger)
* Icônes: vidéo et exemples
* Cards: simple, avec image, triples
* Alertes: exemples
* Couleurs: exemple dans les boutons et les alertes
* Accordéon: exemples et vidéo


Astuces pour designer les pages de cours.

# Listes
Aérez vos instructions avec ces listes plus sympathiques

[![Moodle Design Listes](https://i.ytimg.com/vi/JdeyVMi2W8U/hqdefault.jpg)](
https://www.youtube.com/watch?v=JdeyVMi2W8U)

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

[![Moodle Bootstrap Entête Jumbotron](https://i.ytimg.com/vi/MjYRA2s07C0/hqdefault.jpg)](
https://www.youtube.com/watch?v=MjYRA2s07C0)

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

[![Moodle Design Boutons et Liens](https://i.ytimg.com/vi/73FQHTYExRw/hqdefault.jpg)](
https://www.youtube.com/watch?v=73FQHTYExRw)

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

[![Moodle Icônes FontAwesome](https://i.ytimg.com/vi/tFZ0o1M-PtQ/hqdefault.jpg)](
https://www.youtube.com/watch?v=tFZ0o1M-PtQ)

https://fontawesome.com/v4/icons/

<details>
  <summary><b>Dépliez pour voir les liens et le code</b></summary>
  
* FontAwesome 4: https://fontawesome.com/v4/icons/
  
``<i class="fa fa-address-book" aria-hidden="true"></i>``
  Pour des raisons d'accessibilité le code suivant serait toutefois préférable:
``<span class="fa fa-address-book" aria-hidden="true"></span>``
  
  </details>

# Couleurs
Excellent pour créer des contenus en harmonie avec le reste du site de votre école.

[![Moodle Icônes FontAwesome](https://i.ytimg.com/vi/F9Fw0PjaUOA/hqdefault.jpg)](
https://www.youtube.com/watch?v=F9Fw0PjaUOA)

*Rappelez à votre admin d'ajouter ces couleurs au fichier css de l'appli mobile.

# Accordéon

Vos étudiants se sentent parfois submergé par une longue liste d'actions à réaliser ?
Vous aimeriez qu'ils ou elles puissent afficher progressivement les ressources que vous leur avez préparé?
Voici l'accordéon, déjà inclus dans moodle, accessible par un simple copier coller 😍


[![Moodle Design Accordéon](https://i.ytimg.com/vi/_GxoVIpuLuE/hqdefault.jpg)](
https://www.youtube.com/watch?v=_GxoVIpuLuE)

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

