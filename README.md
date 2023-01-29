## Template pour docker

Un repertoire avec les fichiers nécéssaires à la création d'un container Docker, prêt à l'emploi.

### Mode d'emploi

- Cloner ce repo dans le dossier voulu,
- Ouvrir *docker-compose.yml* et *docker.env* dans votre éditeur de code,
- Remplacer les occurences "template" par le nom choisi (attention à rester cohérent),
- Se rendre dans le dossier via le terminal et utilisé  *"docker-compose up"* .
- Dans docker, le container est créé. Attention cependant au chiffre du localhost, si un container tourne déjà avec le 80:80 vous devrez soit arrêter ce dernier ou bien changer le chiffre pour un autre dans le *docker-compose.yml*.