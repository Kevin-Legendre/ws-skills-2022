# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
- les normes `ecmascript` ✔️
- l'utilisation de l'`asynchrone` ✔️
- les spécifités du mot-clef `this` ✔️

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

```javascript
const url = ('https://api.github.com/users/Kevin-Legendre')

const getGithubProfileInfo = async () => {
  try {
    const response = await fetch(url)
    const data = await response.json()
    console.log('data: ', data)
  } catch (err) {
    console.error('Une erreur est survenue')
  }
}

getGithubProfileInfo()
```

### Utilisation dans un projet ✔️

[lien github](https://github.com/Kevin-Legendre/les_argonauts)

Description : Project du test technique pour les admissions de l'école avce un framework

### J'ai utilisé ce langage en production ✔️

[lien du projet](...)

❌ avoir des projets à montrer

Description : je n'ai pas de projet personnel en production. En revanche les projets d'entreprise le sont.

### J'ai utilisé ce langage en environement professionnel ✔️

Description : j'utilise JS au quotiden en entreprise, avec des frameworks react, vue, avec Node.js etc..

## 🌐 J'utilise des ressources

### Understanding ECMAScript 6

- https://www.amazon.com/Understanding-ECMAScript-Definitive-JavaScript-Developers/dp/1593277571
- pour approfondir mes compétances

## 🚧 Je franchis les obstacles

### Point de blocage ❌

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

