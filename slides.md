---
theme: light-icons
fonts:
  sans: Montserrat
  serif: Montserrat Regular
title: Projet Virtuart
drawings:
  persist: false
transition: slide-up
mdc: true
overviewSnapshots: true


layout: dynamic-image
image: "./media/Pictures/Eclosion.png"
upperImage: "./media/Pictures/Eclosion.png"
equal: true
left: false
---

<div>
<img src="./media/Pictures/VirtuArtLogo2.png"/>
<p style="color:#D8B192;">L'art pour tous!</p>
</div>

<div>
<p style="font-size: 10px;">Présenté par <strong>GOGUET Damien</strong>, <br/> de la promo 2024 à la <strong>Wild Code School</strong>.</p>
<p style="font-size: 10px;">Pour le titre professionnel <strong>développeur web full stack.</strong></p>
</div>

<div class="absolute left-40% m--12 flex gap-2">
  <a href="https://github.com/dampherrr/P3-VirtuArt" target="_blank" alt="GitHub" title="GitHub: P3-VirtuArt"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-black">
    <carbon-logo-github />
  </a>
</div>
---
transition: slide-up
---

# Membre de l'équipe sur le projet:

<div class="team-members">
  <a class="member" href="https://github.com/BaptisteFredj" target="_blank">
    Baptiste <br>
    <img src="https://avatars.githubusercontent.com/BaptisteFredj" target="_blank" alt="BaptisteFredj" width="100" height="100">
  </a>
  <a class="member" href="https://github.com/Agraheris" target="_blank">
    Clément <br>
    <img src="https://avatars.githubusercontent.com/Agraheris" target="_blank" alt="Agraheris" width="100" height="100">
  </a>
  <a class="member" href="https://github.com/dampherrr" target="_blank">
    Damien <br>
    <img src="https://avatars.githubusercontent.com/dampherrr" target="_blank" alt="Dampherrr" width="100" height="100">
  </a>
  <a class="member" href="https://github.com/Ryokoh-974" target="_blank">
    Daniel <br>
    <img src="https://avatars.githubusercontent.com/Ryokoh-974" target="_blank" alt="Ryokoh-974" width="100" height="100">
  </a>
  <a class="member" href="https://github.com/monica-tech75" target="_blank">
    Monica <br>
    <img src="https://avatars.githubusercontent.com/monica-tech75" target="_blank" alt="monica-tech75" width="100" height="100">
  </a>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
  margin-bottom: 5rem;
}

.team-members {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

.member { 
  border-bottom: 4px solid #E0C1A8;
  border-radius: 8px;
  text-align: center;
  margin: 10px;
}
.member:hover { 
  background-color: #E0C1A8;
  color: #090A09;
}
.team-members a img {   
border-radius: 8px;
}
</style>

---
transition: slide-up
level: 2
---

# Demande du client:

<div class="client">
<div v-click class="rules" v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<p>- Gallerie d'art</p>
<img src="./media/Icones/Gallery.jpg" width="100" height="100">
</div>
<div v-click class="rules"   v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<p>- Interactif</p>
<img src="./media/Icones/Interactive.png" width="100" height="100">
</div>
<div v-click class="rules"   v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<p>- Différents profils utilisateurs</p>
<img src="./media/Icones/Users.png" width="100" height="100">
</div>
<div v-click class="rules"   v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<p>- Ajout des favoris</p>
<img src="./media/Icones/Favorite.png" width="100" height="100">
</div>
<div v-click class="rules"   v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<p>- Responsive</p>
<img src="./media/Icones/Responsive.jpg" width="100" height="100">
</div>
<div v-click class="rules"   v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<p>- Deadline</p>
<img src="./media/Icones/deadline.png" width="100" height="100">
</div>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}

.client {

  display: grid;
  grid-template-columns: repeat(3, 1fr);
  justify-items: center;
  align-items: center; 
}

.rules {    
  border-bottom: 4px solid #E0C1A8;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 10px;
  height: 100%; 
}
.rules:hover { 
  background-color: #E0C1A8;
  color: #090A09;
}
</style>

---
layout: dynamic-image 
image: './media/Pictures/Vie_Urbaine.webp'
equal: true
left: true
transition: slide-left
---

# Introduction

<div class="client">
<div v-click v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
<p>- Organisation du projet</p>
</div>
<div v-click v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
<p>- Design</p>
</div>
<div v-click v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
<p>- La modélisation de la base de donnée</p>
</div>
<div v-click v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
<p>- Backend </p>
</div>
<div v-click v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
<p>- Sécurité</p>
</div>
<div v-click v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
<p>- Frontend</p>
</div>
<div v-click v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
<p>- Récap et conclusion</p>
</div>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
  margin-bottom: 5rem;
}

.team-members {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

.member { 
  border-bottom: 4px solid #E0C1A8;
  border-radius: 8px;
  text-align: center;
  margin: 10px;
}
.member:hover { 
  background-color: #E0C1A8;
  color: #090A09;
}
.team-members a img {   
border-radius: 8px;
}
</style>
---
transition: slide-up
layout: image-right
image: './media/Pictures/Backlog.png'
equal: true
left: false
---

# Organisation du projet

## Méthodologie

<div v-click class="method" v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<div class="element">
<p>- Agile (Scrum)</p>
<img src="./media/Icones/Scrum.webp" width="60" height="60">
</div>
</div>
<br>

## Organisation et communication

<div v-click class="orga" v-motion
  :initial="{ y: 80 }"
  :enter="{ x: 0, y: 0 }">
<div class="element">
<p>- Discord</p>
<img src="./media/Icones/discord.svg" width="60" height="60">
</div>
<div class="element">
<p>- FigJam</p>
<img src="./media/Icones/figma.png" width="60" height="60">
</div>
<div class="element">
<p>- Google Sheet</p>
<img src="./media/Icones/GoogleSheets.png" width="40" height="40">
</div>
</div>

<div class="absolute left-60% m-4 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}

.orga, .method {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  justify-items: center;
  align-items: center; 
}
.element{
  border-bottom: 4px solid #E0C1A8;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 10rem;
}
  .element:hover { 
    background-color: #E0C1A8;
    color: #090A09;
  }
</style>

---
layout: two-cols
layoutClass: gap-16
transition: slide-up
---

# Design

## Recherche et inspiration

  <a href="https://www.carredartistes.com/fr-fr/" target="_blank">
    Carré d'artistes<br>
    <img src="./media/Pictures/Carredartistes.png" alt="Carré d'artistes" width="1000" height="100">
  </a>

::right::

## Charte graphique

<img src="./media/Pictures/palette.png" alt="Carré d'artistes" width="1000" height="100">
<br>

## Typography

<p>Monserrat</p>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
</style>

---
layout: two-cols
transition: slide-up
---

# Design

<br>

## Maquettage
<a>
<p>- Figma</p>
<img src="./media/Icones/figma.png" width="100" height="100">
</a>
::right::
<br>
<br>
<br>
<a>
<img src="./media/Pictures/Figma.png" width="1500" height="1000">
</a>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
</style>
---
transition: slide-left
---

# Modélisation de la base de donnée
<br>

<div class="client">
<a style="background-color: #E0C1A8; border-radius: 8px; border: none;">
<h3>Prototypage</h3>
<p>- Draw.io</p>
<img src="./media/Icones/drawio.png" width="70" height="70" >
</a>
<a style="background-color: #F0F0F0; border-radius: 8px; border: none;">
<h3>Méthodologie</h3>
<p>- Méthode Merise</p>
<img src="./media/Icones/merise.png" width="100" height="100">
</a>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  justify-items: center;
  align-items: center; 
}

.client a {
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 10px;
  height: 100%; 
}
</style>

---
layout: image-right
image: './media/Pictures/MCD.drawio.png'
equal: true
left: false
transition: slide-left
---

<div class="text">
  <h2 v-click.hide="1">
    <strong>M C D</strong>
  </h2>

  <h2 v-click="1" v-motion
      :initial="{ x: -80 }"
      :enter="{ x: 0 }">
    <strong>M</strong><span>odèle</span>
    <strong> C</strong><span>onceptuelle de </span>
    <strong> D</strong><span>onnée</span>
  </h2>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
.text {
  position: relative;
  width: 100%;
  max-width: 1000px;
}

.text h2 {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: auto;
}
</style>
---
layout: image-left
image: './media/Pictures/MLD.drawio.png'
equal: true
left: false
transition: slide-left
---

<div class="text">
  <h2 v-click.hide="1">
    <strong>M L D</strong>
  </h2>

  <h2 v-click="1" v-motion
      :initial="{ x: -80 }"
      :enter="{ x: 0 }">
    <strong>M</strong><span>odèle</span>
    <strong> L</strong><span>ogique de </span>
    <strong> D</strong><span>onnée</span>
  </h2>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
.text {
  position: relative;
  width: 100%;
  max-width: 1000px;
}

.text h2 {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: auto;
}
</style>
---
layout: image-right
image: './media/Pictures/MPD.drawio.png'
equal: true
left: false
transition: slide-left
---

<div class="text">
  <h2 v-click.hide="1">
    <strong>M P D</strong>
  </h2>

  <h2 v-click="1" v-motion
      :initial="{ x: -80 }"
      :enter="{ x: 0 }">
    <strong>M</strong><span>odèle</span>
    <strong> P</strong><span>hysique de </span>
    <strong> D</strong><span>onnée</span>
  </h2>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
.text {
  position: relative;
  width: 100%;
  max-width: 1000px;
}

.text h2 {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: auto;
}
</style>
---
transition: slide-left

---

# Backend
<br>

## Les technos utilisées
<br>

<div v-click class="client">
<a style="background-color: #E0C1A8; border-radius: 8px; border: none;">
<p>- MySQL</p>
<img src="./media/Icones/mysql.png" width="50" height="50" >
</a>
<a style="background-color: #F0F0F0; border-radius: 8px; border: none;">
<p>- Express</p>
<img src="./media/Icones/express.png" width="50" height="50">
</a>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding-bottom: 10px;
  margin-bottom:10px;
  height: 100%; 
}

</style>

---
transition: slide-left
level: 3
---


## Base de donnée

Exemple de la table 'artwork':

````md magic-move {lines: true}
```sql {*|2,10|3|5|*}
// Étape 1
create table artwork (
    id INT UNSIGNED PRIMARY KEY AUTO_INCREMENT NOT NULL,
    title VARCHAR(100) NOT NULL,
    image_url VARCHAR(255) DEFAULT "/assets/avatar_user/default.png",
    description TEXT,
    user_id INT unsigned,
    collection_id INT unsigned,
    FOREIGN KEY (user_id) REFERENCES user (id) ON DELETE CASCADE
);
```
```sql {*|2-3,9|4-8|10,18|11-17|*}
// Étape 2
INSERT INTO
    artwork (
        title,
        image_url,
        description,
        user_id
        collection_id
    )
VALUES (
        'Éclosion',
        '/assets/images/PicturesTest/Eclosion.webp',
        'Une peinture abstraite représentant une explosion de couleurs vives.',
        'Peinture à l\'huile',
        '2023-02-15',
        3,
        1
    );
```
````

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

---
layout: image-left
image: './media/Pictures/MVC.png'
equal: true
left: false
transition: slide-left
---

# Architecture

<div class="text">
  <h2 v-click.hide="1">
    <strong>M V C</strong>
  </h2>

  <h2 v-click="1" v-motion
      :initial="{ x: -80 }"
      :enter="{ x: 0 }">
    <strong> M</strong><span>odel</span>
    <strong> V</strong><span>iew</span>
    <strong> C</strong><span>ontroller</span>
  </h2>
</div>


<div class="abs-br m-8 flex gap-2">
  <img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
.text {
  position: relative;
  width: 100%;
  max-width: 1000px;
}

.text h2 {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: auto;
}
</style>
---
layout: two-cols
transition: slide-left
level: 3
equal: true
left: false
---

## Exemple de **modèle**
### ArtworkRepository.js

````md magic-move {lines: true}
```js {*|6-14} 
class ArtworkRepository extends AbstractRepository {
  constructor() {
    super({ table: "artwork" });
  }

  async readAll() {
    const [rows] = await this.database.query(
      `select artwork.*,
      DATE_FORMAT(date, '%d/%m/%Y') AS formatedDate, 
      user.pseudo user_name FROM ${this.table} 
      INNER JOIN user on artwork.user_id = user.id`
    );
    return rows;
  }
} 

module.exports = ArtworkRepository;
```
```js {6-16} 
class ArtworkRepository extends AbstractRepository {
  constructor() {
    super({ table: "artwork" });
  }

  async read(id) {
    const [rows] = await this.database.query(
      `select artwork.*,
      DATE_FORMAT(date, '%d/%m/%Y') AS formatedDate, 
      user.pseudo user_name from ${this.table}  
      INNER JOIN user ON artwork.user_id = user.id 
      WHERE artwork.id = ? `,
      [id]
    );
    return rows[0];
  }
} 

module.exports = ArtworkRepository;
```
````
::right::
# Exemple de **Vue**

<div v-click class="abs-tr m-38 flex gap-2">
<img src="./media/Pictures/Artwork.png" width="200" height="100"/>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>

.imgExpress{display:flex;justify-content:center;align-items:center;}

</style>
---
transition: slide-left
level: 3
---

## Exemple de **Controller**
### artworkActions.js
````md magic-move {lines: true}
```js {*} 
const tables = require("../../database/tables");

const browse = async (req, res, next) => {
  try {
    const artworks = await tables.artwork.readAll();
    res.json(artworks);
  } catch (error) {
    next(error);
  }
};
module.exports = { browse, read, add, edit, destroy};
```
```js {*} 
const tables = require("../../database/tables");

const read = async (req, res, next) => {
  try {
    const artwork = await tables.artwork.read(req.params.id);
    if (artwork == null) {
      res.sendStatus(404);
    } else {
      res.json(artwork);
    }
  } catch (error) {
    next(error);
  }
};
module.exports = { browse, read, add, edit, destroy};
```
````
<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>
---
layout: two-cols
equals: false
transition: slide-up
---

## Routes de l’application

### Router.js

````md magic-move {lines: true}
```js {*|1-2|4|7|8|6-11|*} 
const express = require("express");
const router = express.Router();

const artworks = require("./controllers/artworkActions");

// ARTWORK
router.get("/artworks", artworks.browse);
router.get("/artworks/:id", artworks.read);
router.post("/artworks", middleware.uploadImg, verifyToken, artworks.add);
router.delete("/artworks/:id", artworks.destroy);
router.put("/artworks/:id", artworks.edit);
```
````
::right::

<div v-click="3" v-click.hide="5" style="display: flex; align-items: center;">
  <img v-click="3" v-click.hide="5" src="./media/Icones/postman.png" width="50"/>
  Test des routes sur Postman
</div>

<div class="image">
  <img v-click="3" v-click.hide="4" src="./media/Pictures/postmanreadall.png" width="600"/>
  <img v-click="4" v-click.hide="5" src="./media/Pictures/postmanreadid.png" width="600"/>
</div>

<div class="abs-br m-8 flex gap-2">
  <img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
.image {
  position: relative;
  width: 100%;
  max-width: 1000px;
}

.image img {
  position: absolute;
  top: 0;
  left: 0;
  width: 80%;
  height: auto;
}
</style>
---
layout: two-cols
transition: slide-left
---

# Sécurité de l'application

## Hashage de mot de passe
<br>
<div class="client">
<a style="background-color: #E0C1A8; border-radius: 8px; border: none;">
<p>- Argon2</p>
<img src="./media/Icones/argon2.png" width="50" height="50">
</a>
</div>

::right::
### Middleware: auth.js

````md magic-move {lines: true}
```js {*|1,23|2-7|8-22} 
const argon2 = require("argon2");
const hashingOptions = {
  type: argon2.argon2id,
  memoryCost: 19 * 2 ** 10,
  timeCost: 2,
  parallelism: 1,
};
const hashPassword = async (req, res, next) => {
  try {
    const { password } = req.body;
    const hashedPassword = await argon2.hash(password,
     hashingOptions);

    req.body.hashedPassword = hashedPassword;

    delete req.body.password;

    next();
  } catch (err) {
    next(err);
  }
};
module.exports = {hashPassword};
```
````
<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding-bottom: 10px;
  margin-bottom:10px;
  height: 100%; 
}
</style>
---
layout: two-cols
transition: fade
---

# Sécurité de l'application


## Authentification
<br>
<div class="client">
<a style="background-color: #F0F0F0; border-radius: 8px; border: none;">
<p>- JWT (JSON Web Token)</p>
<img src="./media/Icones/JWT.png" width="50" height="50" >
</a>
</div>

::right::

### Controller: authActions.js

````md magic-move {lines: true}
```js
const argon2 = require("argon2");
const jwt = require("jsonwebtoken");
const tables = require("../../database/tables");
const login = async (req, res, next) => {
  try {
    const user = await tables.user.readByEmailWithPassword(req.body.email);
    if (user == null) {
      res.sendStatus(422);
      return;}
    const verified = await argon2.verify(
      user.hashed_password,
      req.body.password);
    if (verified) {
      delete user.hashed_password;
      const token = await jwt.sign(
        { sub: user.id, isAdmin: user.is_admin },
        process.env.APP_SECRET,
        {expiresIn: "1h",});
      res.cookie("auth", token).json({
        token, user,});
    } else {res.sendStatus(422);}
  } catch (err) {next(err);}
};
const admin = async (req, res, next) => {
  try {
    res.sendStatus(200);
  } catch (error) {
    next(error);
  }
};
module.exports = {login, admin,};
```
```js
const jwt = require("jsonwebtoken");
const login = async (req, res, next) => {
  try {
[...]
    if (verified) {
      delete user.hashed_password;
      const token = await jwt.sign(
        { sub: user.id, isAdmin: user.is_admin },
        process.env.APP_SECRET,
        {expiresIn: "1h",});
      res.cookie("auth", token).json({
        token, user,});
    } else {res.sendStatus(422);}
  } catch (err) {next(err);}};
[...]
module.exports = {login, admin,};
```
````
<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding-bottom: 10px;
  margin-bottom:10px;
  height: 100%; 
}
</style>
---
layout: two-cols
transition: slide-left
---

# Sécurité de l'application


## Vérification des Tokens
<br>
<div class="client">
<a style="background-color: #E0C1A8; border-radius: 8px; border: none;">
<p>- JWT (JSON Web Token)</p>
<img src="./media/Icones/JWT.png" width="50" height="50" >
</a>
</div>

::right::

### Middleware: auth.js

````md magic-move {lines: true}
```js
const jwt = require("jsonwebtoken");
const verifyToken = (req, res, next) => {
  try {
    const { auth } = req.cookies;
    if (!auth) {
      throw new Error("");
    }
    req.auth = jwt.verify(auth, process.env.APP_SECRET);
    req.body.user_id = req.auth.sub;
    next();
  } catch (err) {
    console.error(err.message);
    res.status(401).json({ message: "Unauthorized: Invalid or missing token" });
  }
};
module.exports = {verifyToken,};
```
````
<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding-bottom: 10px;
  margin-bottom:10px;
  height: 100%; 
}
</style>
---
layout: two-cols
equal: true
transition: slide-left
---

# Sécurité de l'application

## Protection des API
<br>
<div class="client">
<a style="background-color: #F0F0F0; border-radius: 8px; border: none;">
<p>- Cors</p>
<img src="./media/Icones/cors.jpg" width="50" height="50">
</a>
<a style="background-color: #E0C1A8; border-radius: 8px; border: none;">
<p>- Cookie-Parser</p>
<img src="./media/Icones/cookie.png" width="50" height="50" >
</a>
<a style="background-color: #F0F0F0; border-radius: 8px; border: none;">
<p>- DotEnv</p>
<img src="./media/Icones/dotenv.png" width="50" height="50">
</a>
</div>

::right::

### Cors: config.js

````md magic-move {lines: true}
```js
const cors = require("cors");
app.use(cors({
  origin: [process.env.CLIENT_URL],  
credentials: true,
})
);
```
````
### cookieParser: config.js
````md magic-move {lines: true}
```js
const cookieParser = require("cookie-parser");
app.use(cookieParser());
```
````
### Dotenv: .env (back)
````md magic-move {lines: true}
```js
# .env.sample - Sample Environment Variables
# Application Configuration
APP_PORT=3310
APP_SECRET=YOUR_APP_SECRET_KEY
# Database Configuration
DB_HOST=localhost
DB_PORT=3306
DB_USER=********
DB_PASSWORD=************
DB_NAME=virtuart
# Client URL (for CORS configuration)
CLIENT_URL=http://localhost:3000
```
````
<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding-bottom: 10px;
  margin-bottom:10px;
  height: 100%; 
}

</style>
---
layout: two-cols
equal: true
transition: slide-left
---

## Validation et Téléchargement de Données
<br>

<div class="client">
<a style="background-color: #F0F0F0; border-radius: 8px; border: none;">
<p>- Joi</p>
<img src="./media/Icones/images.png" width="80" height="80" >
</a>
<!-- <a style="background-color: #E0C1A8; border-radius: 8px; border: none;">
<p>- Multer</p>
<img src="./media/Icones/multer.png" width="80" height="80">
</a> -->
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

::right::

### auth.js
````md magic-move {lines: true}
```js
const Joi = require("joi");
const verifyUserField = (req, res, next) => {
  const schema = Joi.object({
    pseudo: Joi.string().required(),
    email: Joi.string().email().required(),
    password: Joi.string().min(8).required(),
    confirmPassword: Joi.ref("password"),
  });
  const result = schema.validate(req.body);
  if (result.error) {
    res.status(400).send(result.error.message);
  } else {
    next();
  }
};
module.exports = {verifyUserField,};
```
````

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding-bottom: 10px;
  margin-bottom:10px;
  height: 100%; 
}

</style>
---
layout: two-cols
equal: true
transition: slide-left
---

## Validation et Téléchargement de Données

<div class="client">
<a style="background-color: #E0C1A8; border-radius: 8px; border: none;">
<p>- Multer</p>
<img src="./media/Icones/multer.png" width="80" height="80">
</a>
</div>

## Génération et Sécurisation des Identifiants Uniques

<div class="client">
<a style="background-color: #F0F0F0; border-radius: 8px; border: none;">
<p>- UUID</p>
<img src="./media/Icones/uuid.png" width="50" height="50" >
</a>
</div>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

::right::

### middleware.js
````md magic-move {lines: true}
```js {*|1,17|2-5,12|6-11|13-16|*}
const multer = require("multer");
const storage = multer.diskStorage({
  destination(req, file, cb) {
    cb(null, "./public/assets/images/uploads");
  },
  filename(req, file, cb) {
    const id = uuidv4();
    const pictureName = `${id}${path.extname(file.originalname)}`;
    req.body.image_url = `/assets/images/uploads/${pictureName}`;
    cb(null, pictureName);
  },
});
const uploadImg = (req, res, next) => {
  const upload = multer({ storage });
  return upload.single("image")(req, res, next);
};
module.exports = {uploadImg};
```
````

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100%; 
}

</style>
---
layout: two-cols
equal: true
transition: slide-left
---

## Contrôle d'Accès et Gestion des Rôles
<br>

````md magic-move {lines: true}
```sql {*}
CREATE TABLE user (
[...]
    is_admin BOOLEAN DEFAULT FALSE
);
INSERT INTO
    user (
      [...]
      is_admin
    )
VALUES (
  [...]
    '0'||'1'
    )
```
````

::right::

## Sécurisation de la Base de Données
<br>

````md magic-move {lines: true}
```sql {*|2|3-5|6-10|*}
  async create(artwork) {
    const [result] = await this.database.query(
      `INSERT INTO artwork 
      (title,image_url, description, technique, date, user_id) 
      VALUES(?, ?, ?, ?, CURDATE(), ?)`,
      [ artwork.title,
        artwork.image_url,
        artwork.description,
        artwork.technique,
        artwork.user_id, ]
    );
    return result;
  }
```
````
## Sécurisation des Dépendances
<br>

<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>

<style>
  h1 {
    color: #D8B192;
}
.client {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  justify-items: center;
  align-items: center;   
}

.client a {
  width: 10rem;
  min-height: 10rem;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding-bottom: 10px;
  margin-bottom:10px;
  height: 100%; 
}

</style>


---
---

## level: 2
<div class="abs-br m-8 flex gap-2">
<img src="./media/Pictures/VirtuArtLogo2.png" width="30" height="30"/>
</div>
---
