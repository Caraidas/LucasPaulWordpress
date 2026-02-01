git : https://github.com/Caraidas/LucasPaulWordpress

- étape 1
etre dans un terminale 
- étape 2
se rendre dans le dossier wordpress-prod
- etape 3
entrez les commandes suivante dans le terminale : 
minikube addons enable ingress
kubectl apply -k .\stack\
- etape 4
lancez le wordpress via la commande suivante : 
    minikube service nginx
    