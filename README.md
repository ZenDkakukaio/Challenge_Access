# Challenge_Access
petit challenge de steganographie pour les passionnés de bidouillage et cracking.


![step](https://github.com/ZenDkakukaio/Challenge_Access/assets/84296565/b0a46f81-c14a-4488-a429-717df76caac2)


tu dois te connecter depuis une plateforme web tournant sur un serveur local deployé sous Django.
pour te loguer, il est necessaire de recuperer une clé. 
la clé est dissimulée dans une image cryptée qui contient une boite bleue. la dite boite contient un nombre de pixel qu'il va falloir recuperer.
vous devrez creer un script qui vous donne la posibilité d'identifier le nombre de pixel avec lesquels a ete genéré la boite bleue.
apres avoir identifié et recuperer la longeur des pixels de la boite dans l'image, vous devrez faire une correspodance entre le nombre de pixel de la boite et les positions des lettres de l'alphabet comme suit: supposons que vous avez trouver 32 pixels alors vous aurez 3 correspondant à la lettre c et b ce qui vous donnera comme clé d'authentification la sequence CB. 
aucune lettre n'a pour rang 0 du coup 0 vaudra toujours 0 lors de la correspondance. les representation finales sont en Miniscule.
BON CHALLENGE!!!!!
![instructions](https://github.com/ZenDkakukaio/Challenge_Access/assets/84296565/443c00cb-cef2-42f1-b268-1c722f260b6a)
