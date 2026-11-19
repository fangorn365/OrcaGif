# OrcaGif – Créateur et éditeur de GIF gratuit et privé

[English](README.md) · [Deutsch](README.de.md) · **Français** · [Español](README.es.md) · [العربية](README.ar.md) · [हिन्दी](README.hi.md) · [中文](README.zh.md) · [বাংলা](README.bn.md) · [Português](README.pt.md) · [Bahasa Indonesia](README.id.md)

Transformez une vidéo en GIF, modifiez un GIF que vous avez déjà ou enregistrez le résultat en WebP ou WebM, des fichiers bien plus légers. OrcaGif tient dans un seul fichier HTML. Tout se passe localement dans votre navigateur : pas d’envoi de fichiers, pas de compte, pas de cookies.

## Démarrage rapide
1. Ouvrez `OrcaGif.html` dans votre navigateur.
2. Choisissez un onglet en haut : **🎬 Vidéo en GIF** (créer un GIF à partir d’une vidéo) ou **🎨 Éditeur GIF** (modifier un GIF, une image, une vidéo, un WebP ou un WebM que vous avez déjà).
3. Choisissez le type de fichier (GIF, WebP ou WebM), cliquez sur le bouton bleu et téléchargez le résultat.

> Le guide « Comment ça marche – guide rapide et FAQ » en haut de la page explique les mêmes étapes avec des mots simples, dans les 10 langues.

## Quel type de fichier choisir ?
- **GIF** fonctionne partout (messageries, forums, e-mail), mais les fichiers sont plus lourds. Un doute ? Choisissez GIF.
- **WebP** est bien plus léger que le GIF, plus beau, et peut avoir un fond transparent. Tous les navigateurs récents l’affichent, certains anciens logiciels non.
- **WebM** est le plus léger et le plus fluide, mais c’est une vidéo : pas de fond transparent, et la création dure plus longtemps que l’extrait (enregistrement en temps réel – gardez l’onglet au premier plan).
- **Qualité** (WebP et WebM) : haute, moyenne ou basse. Une qualité plus basse donne un fichier plus léger.
- Si WebP ou WebM est grisé, votre navigateur ne peut pas créer ce format. Utilisez une version récente de Chrome, Edge ou Firefox.

## Créer un GIF à partir d’une vidéo – pas à pas
1. Cliquez sur l’onglet **🎬 Vidéo en GIF**.
2. Cliquez sur le bouton de fichier à gauche et choisissez une vidéo sur votre appareil (MP4 et WebM fonctionnent dans tous les navigateurs modernes ; MKV et HEVC dépendent du navigateur et de l’appareil). Rien n’est envoyé, et même les fichiers de plusieurs Go fonctionnent.
3. Choisissez la partie voulue : faites glisser sur la barre sous la vidéo, utilisez **Définir le début ici** / **Définir la fin ici** (touches `I` / `O`) ou saisissez les heures. **▶ Lire l’extrait** montre un aperçu. Les extraits courts de 2 à 6 secondes fonctionnent le mieux.
4. Réglez la **Largeur de sortie** (la largeur du GIF ; 480 est un bon début) et les **FPS** (images par seconde ; 15 paraît fluide). Des valeurs plus petites donnent un fichier plus léger.
5. Choisissez le type de fichier et appuyez sur le bouton bleu. Gardez l’onglet au premier plan jusqu’à ce que la barre soit pleine.
6. Appuyez sur le bouton bleu de téléchargement. Pour un GIF, vous pouvez d’abord cliquer sur **Modifier dans l’éditeur GIF** pour ajouter du texte.

## Modifier un GIF que vous avez déjà
1. Ouvrez l’onglet **🎨 Éditeur GIF** et choisissez votre fichier à gauche : un GIF, une image, une vidéo, un **WebP animé** ou un **WebM**. Le glisser-déposer fonctionne aussi.
2. Appuyez sur ▶ pour lire. Déplacez le curseur pour voir les images une par une (frames).
3. Sous **Modifier** : **Image de début** / **Image de fin** suppriment le début ou la fin, **Vitesse ×** accélère ou ralentit, **Inverser** lit à l’envers, **FPS** (max. 50) et **Largeur de sortie** changent la fluidité et la taille, **Recadrer** découpe l’image.
4. Choisissez le type de fichier, appuyez sur le bouton bleu et téléchargez le résultat. Une erreur ? Appuyez sur **Annuler** en haut.

## Ajouter du texte, des images et des dessins
- **+ Texte** ajoute des mots sur votre GIF. Saisissez-les dans la zone à gauche, choisissez police, taille et couleur, puis faites glisser le texte au bon endroit. **Double-cliquez sur le texte dans l’image pour le modifier à nouveau** (ou double-cliquez dessus dans la liste des calques).
- **+ Image** ajoute votre propre image, par exemple un logo. **✏️ Dessiner** permet de dessiner à la souris ou au doigt.
- Chaque texte, image ou dessin est un **calque**. Cliquez sur un calque dans la liste pour le sélectionner ; ▲ ▼ le montent ou le descendent, ✕ le supprime. **Visible à partir de l'image** / **jusqu'à l'image** déterminent quand il s’affiche.
- Molette sur un calque = taille, Maj + molette = rotation. Les calques peuvent aussi être placés hors de l’image (marge assombrie) et récupérés plus tard.

## Faire bouger les éléments
- **La voie rapide :** sélectionnez un texte ou une image et appuyez sur un effet : Fondu entrant, Entrée en volant, Pulsation, Tremblement, Tourner ou Rebondir.
- **À votre façon :** cochez **Animer (images clés)**, allez à une autre image et faites glisser le calque vers un nouvel endroit. OrcaGif calcule le mouvement entre les deux. Choisissez une accélération si vous le souhaitez.

## Que signifient ces mots ?
- **Image (frame)** – une seule image d’une animation. Un GIF est composé de nombreuses images affichées rapidement l’une après l’autre.
- **FPS** – images par seconde. Plus il y en a, plus c’est fluide, mais le fichier grossit.
- **Largeur de sortie** – la largeur du fichier final, en pixels (de minuscules points à l’écran).
- **Tramage (dithering)** – un GIF ne peut utiliser que 256 couleurs. Cette astuce mélange de minuscules points pour que les ciels et la peau paraissent plus doux. Activez-le pour les photos et les vidéos, laissez-le désactivé pour les logos et les dessins en aplats. (GIF uniquement.)
- **Arrière-plan transparent** – les zones transparentes laissent voir ce qui se trouve derrière l’image. Fonctionne avec GIF et WebP.
- **Calque** – un texte, une image ou un dessin posé par-dessus votre GIF.
- **Image clé** – une position, une taille ou un angle enregistré à un instant donné. OrcaGif calcule le mouvement entre deux images clés.
- **Filigrane** – le petit texte « OrcaGif » dans un coin. Il est activé par défaut – merci de le laisser pour soutenir cet outil gratuit.

## Mon fichier est trop volumineux – que faire ?
Utilisez une **Largeur de sortie** plus petite, moins de **FPS** ou un extrait plus court – ou choisissez **WebP**. Si les couleurs d’un GIF paraissent tachetées, activez le **tramage (dithering)**.

## Projets
- **Enregistrer** garde le projet dans votre navigateur pour continuer plus tard.
- **Fichier projet ↓ / ↑** enregistre / ouvre un vrai fichier (`.gifproj`).

## Raccourcis
`Ctrl+Z` annuler · `Ctrl+Y` rétablir · `Ctrl+S` enregistrer · `Ctrl+D` dupliquer le calque · `←` `→` image précédente / suivante · double-clic sur un texte = le modifier · `I` / `O` début / fin (Vidéo en GIF)

---
Projet personnel non commercial. Compteur de visites anonyme et sans cookies ([GoatCounter](https://www.goatcounter.com)). Contact : Discord (lien dans le pied de page de l’application).
