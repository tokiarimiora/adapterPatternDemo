# adapterPatternDemo
Une petite démonstration du design pattern 'adaptateur'.

Le modèle d'adaptateur fonctionne comme un pont entre deux interfaces incompatibles. Ce type de modèle de conception relève d'un modèle structurel car ce modèle combine la capacité de deux interfaces indépendantes.

Ce modèle implique une seule classe qui est chargée de joindre les fonctionnalités d'interfaces indépendantes ou incompatibles. Un exemple concret pourrait être un cas de lecteur de carte qui agit comme un adaptateur entre la carte mémoire et un ordinateur portable. Vous branchez la carte mémoire dans le lecteur de carte et le lecteur de carte dans l'ordinateur portable afin que la carte mémoire puisse être lue via un ordinateur portable.

Nous démontrons l'utilisation du modèle d'adaptateur via l'exemple suivant dans lequel un lecteur audio ne peut lire que des fichiers mp3 et souhaite utiliser un lecteur audio avancé capable de lire des fichiers vlc et mp4.
