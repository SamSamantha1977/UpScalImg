# UpScalImg — dépôt de dépendances exclusivement

Ce dépôt GitHub ne distribue PAS les archives ZIP des skills. Les ZIP légers sont autonomes et fournis séparément.
Ce dépôt contient les dépendances lourdes (GitHub Releases), les manifestes SHA-256 et les références d'origine.

## Moteurs, modèles et distributions

- upscayl-ncnn / windows-x64 : 228459700 octets
  - Téléchargement : https://github.com/SamSamantha1977/UpScalImg/releases/download/deps-v1.0.0/upscayl-ncnn-windows-x64-1.1.0.zip
  - SHA-256 : 006ee0ddfb43b5bbb3ba3be54808af8ed7ca557ccd2c0cc38b022ac8aeb26477
- upscayl-ncnn / linux-x64 : 3952825 octets
  - Téléchargement : https://github.com/upscayl/upscayl-ncnn/releases/download/20251207-174704/upscayl-bin-20251207-174704-linux.zip
  - SHA-256 : a9fab3c770b62f2b7a35d8d6d61eb4e8b3aef79128b665c919d080b85a2292f2
- ffmpeg / windows-x64 : 121652518 octets
  - Téléchargement : https://github.com/SamSamantha1977/UpScalImg/releases/download/deps-v1.0.0/ffmpeg-windows-x64-2025-02-13.zip
  - SHA-256 : 54d99f06e60e16e2f2835eed9c30584e5ddf407ff61e5e7a3a65e5065c67ed5e

## Licences et limites

Conserver THIRD_PARTY_NOTICES.md et les licences d'origine, notamment les conditions propres aux poids IA.
Les moteurs nécessitent le système/architecture correspondant, les bibliothèques compatibles et parfois un GPU Vulkan.
Les modèles et moteurs Windows ne sont pas exécutables sur Linux. Certains poids IA peuvent être communs aux deux systèmes.
Les poids Upscayl d'origine sont référencés dans UPSTREAMS.md; Real-ESRGAN et RIFE sont inclus dans les archives Video2X.
L'exécution réelle des moteurs Linux doit être validée sur une machine Linux équipée d'un GPU compatible.

## Utilisation par la skill

Au lancement d'un mode nécessitant un moteur absent, la skill télécharge les actifs HTTPS épinglés
dans dependencies.json et valide le SHA-256 avant extraction ou exécution.
La variable SAM_SKILL_AUTO_DOWNLOAD=0 empêche tout téléchargement automatique.
