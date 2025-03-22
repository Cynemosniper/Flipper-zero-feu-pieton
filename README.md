# flipper-zero-feu-pieton

# Trame radio pour Flipper Zero : Feux piétons pour personnes malvoyantes

Ce projet propose une trame radio `.sub` pour Flipper Zero, permettant de déclencher les feux piétons pour les personnes malvoyantes en France. En plus de déclencher les feux piétons, cette trame permet également de faire passer les feux pour véhicules au rouge. Elle prend en charge l'audio des feux piétons, un signal sonore qui aide les personnes malvoyantes à savoir quand traverser en toute sécurité.

## Fonctionnalités
- **Feux piétons** : La trame envoie un signal pour allumer les feux piétons et activer l'audio. L'audio des feux piétons est conçu pour émettre un signal sonore distinct, permettant aux personnes malvoyantes de savoir qu'il est sécuritaire de traverser.
- **Feux pour véhicules** : La trame envoie également un signal pour mettre les feux pour véhicules au rouge, arrêtant ainsi la circulation et garantissant la sécurité des piétons.
- **Fréquence de transmission** : La trame est conçue pour être compatible avec les systèmes de feux piétons en France, qui utilisent des fréquences spécifiques pour ce genre de signalisation.
- **Durée d'activation** : La trame permet de maintenir les feux piétons allumés et les feux pour véhicules au rouge pendant un temps suffisant pour permettre une traversée sécurisée, en fonction des paramètres définis par le système.
- **Signal sonore** : En plus de l’aspect visuel, l'audio des feux émet un bruit caractéristique, souvent un bip ou un son cyclique, permettant aux piétons malvoyants de localiser la traversée sûre sans avoir à regarder les feux visuels.

## Utilisation

1. Téléchargez la trame `.sub` et placez-la sur votre Flipper Zero.
2. Activez le module radio sur votre Flipper Zero et lancez la lecture de la trame.
3. La trame déclenchera les feux piétons, activera l'audio des feux (signal sonore), et mettra les feux pour véhicules au rouge, permettant ainsi une traversée sécurisée.

## Avertissement

L'utilisation de cette trame est réservée à un usage légal et responsable. Toute utilisation non autorisée ou malveillante est à la charge de l'utilisateur. L'utilisation de cette trame dans un contexte non prévu, comme pour perturber la circulation, est strictement interdite.

## Licence

Ce projet est distribué sous la licence GPL-3.0.

