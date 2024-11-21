Pour la version française, prière de se diriger plus bas

# Hi! Welcome to Gyromancy's Petit Mot French Reclist Edit!

This resource contains:
- Core reclists to make the base framework of a French CVVC format voicebank
- Extra reclists for broadening the capabilities of your Petit Mot style reclist
- Option reclists with shorter mora strings to substitute lists from this release
- Base oto configs for quick configuration

# 1. The [B]asics

This resource has two use cases:
1. You want to start making a French voicebank for UTAU?
Great! Start with the listed `Core_xx` reclists
2. You want to add different extensions to your existing French voicebank?
Also great! Please check if your voicebank is configured in the Petit Mot format and then choose from the different `Extra_xx` lists

Both use cases have associated base oto.ini files that will give you a starting point of lines when using setParam or vlabeler
The values noted after the reclist name are the length as a number of required recordings, to give an approximation of the time of recording needed

The Gyroflex French Reclist Edit is based on melomad's [Petit Mot CVVC / Gros Mot VCV format](https://github.com/Gyromancyx/Reclist-Gyroflex-FRA)

# 2. Starting from [S]cratch

*Is this your first time recording French? You already have recorded French, but want to try the Petit Mot format?*

Please check out the `Core_CVVC` list first. It will get you acquainted with the vowels and consonants contained in the Continental French singing style. Supplementary resources for pronunciation and example voicebanks can be found on the [utaufrance.com](https://utaufrance.com) resource site
It is suggested to record with a BGM in OREMO at 100BPM

Next is the `Core_VV_7mora` list. It will add vowel transitions to your voicebank. This list is configured with 7mora, which means 7 syllables per line. If this is uncomfortable for you to record, you can substitute it with one of the two option lists, `Opt_VV_5mora` or `Opt_VV_4mora`

Finally, you will need to record the `Core_CC` list. This is needed for a few consonant clusters as well as certain starting and end consonants. Please do not be afraid at the length of the recordings! You can do them at your own pace regardless of BGM or pitch, since you will only be using the consonant parts
The noted vowels on this list are also replaceable! Please use whichever helping vowels make it easiest for you to record, as long as you can naturally pronounce the consonants

Please note: the appended base oto.ini for `Core_CC` is taken 1:1 from my voicebank, Sashoune Yura_Gyrophare. You will need to check it before usage, because it is adapted to the recordings made at the time, which have not been made on a BGM

# 3. Building on [E]xpansion

*You have followed the steps from 2? Or have already recorded a voicebank in the Petit Mot format?*
You may now pick and choose from the `Extras_xx` list. They host different extensions which will extend the capabilities of your voicebank or aid it in sounding more natural

`Extra_Adds` contains end breaths and glottal stops
`Extra_ny` contains CCV sounds for smoother [ny] consonant combinations
`Extra_VCC` contains transitional end consonants. They are used to have a smoother transition between vowels followed by two consonants. Using this, you can substitute some plosive CC endings for [VC.] for a more natural glottal stop, i.e. [ael][lk][kae] can now become [ael.][kae]. Please note that this list's base oto is also taken without modifications from my voicebank and will thus definitely need editing before usage

# 4. Fine-Tuning the [C]onfig

Once you have recorded all the components you like, you will have to configure your voicebank. You can get a quick start on this by dropping the appended base oto.ini files into your associated recording folders. You then only have to rename them to "oto.ini" for them to be read by the following programs
It is recommended to use setParam or vlabeler for configuration instead of Classic UTAU and OpenUTAU's built-in configurators

# 5. Starting [U]sage

You have recorded and configured your voicebank? Congratulations! You can now start using it in UTAU
For getting started in UTAU, please refer to the tutorials found on the [OpenUTAU Github page (English)](https://github.com/stakira/OpenUtau) or on the [utaufrance.com page (French)](utaufrance.com)
If you are using OpenUTAU, you can use the built-in phonemizer for French CVVC contributed by Mim

# 6. Any [Q]uestions?

Did you have trouble? Something missing? Want to give feedback or show your work?
You can contact the [utaufrance Discord server](https://discord.gg/3VZyfSvgP4)
Or contact me directly on [Twitter](https://twitter.com/GyromancyX)

Thank you!

---

# Salut! Bienvenue sur le Petit Mot French Reclist Edit de Gyromancy!

Cette ressource contient:
- Des reclists principales pour créer une base simple de voicebank française
- Des reclists extra pour augmenter les capacités d'une voicebank en format Petit Mot
- Des reclists en option pour substituer les reclists de cette release
- Des oto de base pour les listes de cette page

# 1. The [B]asics

Cette ressource a deux cas d'utilisation:
1. Commencer la création d'une voicebank française?
Super! On peut commencer avec les listes nommées `Core_xx`
2. Ajouter des différentes extensions à une voicebank française existante?
Super aussi! Prière de vérifier si la voicebank est configurée en notation Petit Mot et choisir des différentes listes `Extra_xx`

Les deux sont équipées de listes de configuration oto de base qui fournissent une base de configuration de lignes pour l'utilisation dans setParam ou vlabeler
Les valeurs notées après les noms des listes sont la longueur de la liste en nombre d'enregistrements à faire, pour donner une impression du temps d'enregistrement nécessaire

La liste éditée Gyroflex Français est basée sur la liste [Petit Mot CVVC / Gros Mot VCV format](https://github.com/Gyromancyx/Reclist-Gyroflex-FRA) de melomad

# 2. Starting from [S]cratch

*C'est le premier enregistrement d'une liste française?*

Prière de commencer avec la liste `Core_CVVC`. Elle va introduire les différentes voyelles et consonnes nécessaires pour un style de chant français continental. Des ressources de prononciation et des voicebanks en exemple se trouvent sur [utaufrance.com](https://utaufrance.com) 
Il est recommandé d'enregistrer avec un BGM à 100BPM sur OREMO

Suivante est la liste `Core_VV_7mora`. Elle ajoutera des transitions de voyelles à la liste. La liste prévoit 7mora, donc 7 syllabes par ligne. Si cela n'est pas confortable, il est possible de la substituer par les listes `Opt_VV_5mora` ou `Opt_VV_4mora`

La dernière liste est la `Core_CC`. Elle est nécessaire pour les clusters de consonnes et certaines consonnes de fin et de début. Ne pas être surpris par la longueur des lignes! Il n'est pas nécessaire d'utiliser un BGM ou pitch pour ces lignes, car seulement les parties des consonnes seront utilisées
Les voyelles notées sur cette liste sont également remplaçables. Il est possible d'utiliser n'importe quelle voyelle d'aide, le principe c'est d'avoir une prononciation naturelle 

Prière de noter: 

La configuration de base pour `Core_CC` vient directement de ma voicebank, Sashoune Yura Gyrophare, sans changement. Il sera nécessaire de vérifier la configuration avant l'utilisation, car elle a été enregistrée sans BGM

# 3. Building on [E]xpansion

*Les étapes de la première partie sont finies? Il existe déjà une voicebank format Petit Mot?*

Maintenant il est possible de continuer avec la liste `Extras_xx`. Celles-ci contiennent différents extras qui vont augmenter les possibilités et la fluidité de la voicebank

`Extra_Adds` contient des souffles de fin et des stops glottales
`Extra_ny` contient des combinaisons [ny] pour un aperçu plus naturel
`Extra_VCC` contient des transitions de consonnes transitionnelles. Elles sont utilisées pour un passage plus naturel sur les transitions entre consonnes dans les clusters de deux consonnes et peuvent éviter l'utilisation de CC dans certains cas. Avec ceci, il est possible d'utiliser [VC.] pour une pause glottale plus naturelle avant les consonnes plosives, par exemple [ael][lk][kae] peut maintenant être substitué par [ael.][kae]. Prière de noter que l'oto de base pour cette liste est également une copie de la configuration de ma voicebank et nécessite donc absolument une modification avant l'utilisation

# 4. Fine-Tuning the [C]onfig

Une fois l'enregistrement terminé, il sera nécessaire de configurer la voicebank. La configuration se fera plus vite avec l'utilisation des configurations de base attachées sur ce repo qui peuvent être copiées dans les fichiers correspondants. Il sera seulement nécessaire de les renommer "oto.ini" pour que les programmes suivants puissent les lire.
Il est recommandé d'utiliser setParam ou vlabeler à la place des configurateurs intégrés dans Classic UTAU ou OpenUTAU

# 5. Starting [U]sage

La voicebank est enregistrée et configurée? Félicitations! Il est désormais possible de l'utiliser dans UTAU
Pour commencer avec l'utilisation dans UTAU, prière de se diriger vers les tutoriels sur la page [GitHub pour OpenUTAU](https://github.com/stakira/OpenUtau) ou [utaufrance.com (French)](utaufrance.com)
Si le logiciel de votre choix est OpenUTAU, il est possible d'utiliser le phonemizer préinstallé French CVVC de Mim

# 6. Any [Q]uestions?

Des problèmes? Des manquants? Du feedback?
Voici le [serveur Discord utaufrance](https://discord.gg/3VZyfSvgP4)
Et mon contact direct sur [Twitter](https://twitter.com/GyromancyX)

Thank you!
