#Exercice 2: serveur angular

#Journalisation d'un site web (avec deux routes : home et help sur un serveur angular), sur un fichier .txt, à chaque visite du client.7

# Resolution
1. l'on  installe Angular CLI en utilisant npm. utiliser sudo pour les permissions administratives :
2.vérifiez que Angular CLI est installé correctement 

3. Créer un projet Angular:

4. Générer deux composants pour les routes :

5. Configurer les routes Angular dans app-routing.module.ts :

6.Configurer les composants pour afficher un simple message :

7. Créer un backend Node.js pour journaliser les visites
#Créer un nouveau répertoire pour le backend
mkdir backend
cd backend
npm init -y
npm install express body-parser

8. Créer un fichier server.js :

9.Créer un service Angular pour envoyer les visites au backend :

10.Injecter le service dans les composants :

11. Configurer HttpClientModule dans app.module.ts :
12. pour la journalisation:j'ai utilise une bibliothèque de journalisation winston :

13 Lancer le backend et le frontend
 a. Lancer le backend :

b.Lancer le frontend :
