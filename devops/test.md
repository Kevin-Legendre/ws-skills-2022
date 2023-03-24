# Tester son application

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les tests unitaires ✔️
- les mocks ✔️
- les tests d'integration ✔️
- les tests de bout en bout (end to end) ✔️
- le TDD ✔️
- les tests par snapshot ❌

## 💻 J'utilise

### Un exemple personnel commenté  ✔️


```javascript
describe("Cart", () => {
  // Dans cet exemple on test que le bouton "Purchase" dans le panier est bien rendu
  it("renders a button", () => {
    render(<Cart cancel={() => {}} />);
    expect(screen.getByText(/Purchase/i)).toBeInTheDocument();
  });

  /* Dans cet exemple on simule un clic sur le le bouton "purchase"
     et on test que le texte 'Thank you' s'affiche bien à l'écran
     après le clic sur le bouton
  */
    describe("When user clicks purchase button", () => {
    it("renders Thank you!", () => {
      render(<Cart cancel={() => {}} />);
      fireEvent.click(screen.getByText(/Purchase/i));
      expect(screen.getByText(/Thank you !/i)).toBeInTheDocument();
    });
  });
})

```
### Utilisation dans un projet ✔️

JustOneCar projet de fin d'année

[lien github](https://github.com/WildCodeSchool/2022-11-turing-JustOneCar)

Description :

Dans ce projet nous avons mis en place des test unitaires pour tester des composants coté front,  
pour le coté back de notre appliocation nous avons testé certaines méthodes de l'authentification des utilisateurs.

### Utilisation en production si applicable ❌



Description :

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
