# python-starter-kit
"Boîte à outils pédagogique et exercices corrigés pour débuter en Python."
Il s'adresse aux débutants, aux étudiants en reconversion ou à toute personne souhaitant consolider ses bases algorithmiques.

---

## 📂 Contenu du dépôt

Ce dépôt contient des scripts simples, commentés pas à pas, pour aborder les notions fondamentales de la programmation :

1. **`calcul_imc.py`** : Script de calcul de l'Indice de Masse Corporelle (manipulation des variables, conditions `if/else`, et fonctions).
2. **`jeu_devinette.py`** : Jeu interactif où l'ordinateur choisit un nombre et l'utilisateur doit le trouver (utilisation des boucles `while` et gestion des entrées utilisateur).
3. **`manipulation_listes.py`** : Exemples commentés sur le parcours et le traitement de structures de données de base.

---

## 🚀 Comment utiliser ces scripts ?

### Prérequis
Assurez-vous d'avoir installé **Python** (version 3.8 ou supérieure) sur votre machine.

### Lancer un script
Clonez ce dépôt ou téléchargez-le, puis ouvrez votre terminal dans le dossier du projet :

```bash
python nom_du_script.py

👨‍🏫 À propos

Proposé par Jawad Madkouri — Formateur Indépendant en Informatique, Data & Intelligence Artificielle. Retrouvez mes accompagnements et modules de formation axés sur la pratique et la pédagogie par le projet.


---

### Étape 3 : Ajouter vos premiers scripts (optionnel mais recommandé)
Pour que votre dépôt soit vivant, vous pouvez créer deux ou trois fichiers de code directement sur l'interface de GitHub en cliquant sur **"Add file" > "Create new file"**.

1. Nommez le premier fichier `calcul_imc.py` et collez ce code simple :
```python
def calculer_imc(poids, taille):
    """Calcule l'Indice de Masse Corporelle (IMC)."""
    imc = poids / (taille ** 2)
    return round(imc, 2)

# Exemple d'utilisation
poids_kg = 75
taille_m = 1.75

mon_imc = calculer_imc(poids_kg, taille_m)
print(f"Pour un poids de {poids_kg} kg et une taille de {taille_m} m, l'IMC est de {mon_imc}")

    Cliquez sur "Commit changes..." pour valider.

Et voilà ! En quelques clics, votre profil GitHub n'est plus vierge : vous disposez d'une vitrine propre, professionnelle, et en parfaite adéquation avec votre posture de formateur.

Dites-moi dès que c'est en ligne (ou si vous avez besoin d'aide sur une manipulation technique de l'interface GitHub) !
