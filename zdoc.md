sudo update-alternatives --set php /usr/bin/php8.2
sudo update-alternatives --set php /usr/bin/php8.4



# php bin/console doctrine:fixtures:load --append




# A faire
# Connexion et déconnexion de l’administrateur

# Recherche des articles

# Tri des articles

# Affichage des articles par catégorie

# Pour commenter, il faut être inscrit et connecté

# 1. Installation avec CDN (le plus simple)




✅ 1. Vérifier l’état du projet
git status

✅ 2. Ajouter les fichiers modifiés
git add .

✅ 3. Enregistrer les modifications (commit)
git commit -m "Description de la mise à jour"

✅ 4. Récupérer les dernières mises à jour depuis GitHub (important avant de push)
git pull

✅ 5. Envoyer tes modifications vers GitHub
git push

🔧 Si ton projet n’est pas encore connecté à GitHub


Initialiser Git :
git init

Ajouter l’origine GitHub :
git remote add origin https://github.com/TON-UTILISATEUR/NOM-DU-REPO.git

Pousser la première fois :
git branch -M main
git push -u origin main
