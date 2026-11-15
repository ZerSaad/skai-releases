# SKAI 🌍

Ton compagnon IA pour explorer le monde.

SKAI est une application Windows qui réunit un assistant de voyage, une conversation vocale et un globe 3D interactif.

**[Télécharger la dernière version](https://github.com/ZerSaad/skai-releases/releases/latest)**

## Ce que tu peux faire avec SKAI

- Explorer des destinations et trouver des idées de visites.
- Découvrir les spécialités culinaires et les coutumes locales.
- Te renseigner sur les formalités de visa selon ta nationalité.
- Identifier les meilleures périodes pour voyager.
- Consulter l’heure locale des destinations évoquées.

Le globe se déplace au fil de la conversation et met en lumière les pays mentionnés.

## Parle avec SKAI

Écris dans le chat ou active le mode vocal pour discuter à voix haute.

SKAI peut te saluer au démarrage, écouter ta réponse et te répondre oralement. Tu peux l’interrompre pour reprendre la parole. Une orbe indique l’état de la conversation et tu peux désactiver le vocal à tout moment.

## Télécharger et installer

1. Ouvre la page de la [dernière version](https://github.com/ZerSaad/skai-releases/releases/latest).
2. Dans la section **Assets**, télécharge le fichier `SKAI-Setup-…-x64.exe`.
3. Lance l’installateur et suis les instructions.
4. Ouvre SKAI, puis renseigne ton nom et ta nationalité.

Les archives **Source code (zip)** et **Source code (tar.gz)** sont générées automatiquement par GitHub. Choisis le fichier `.exe` pour installer l’application.

### Configuration nécessaire

- Windows 64 bits.
- Une connexion Internet pour les réponses de l’IA.
- Un microphone pour parler à SKAI.
- Des haut-parleurs ou un casque pour entendre ses réponses.

## Profil et mémoire

SKAI conserve ton profil, tes conversations et les destinations consultées dans une base de données locale sur ton ordinateur, associée à ton compte Windows.

Les échanges sont transmis à Google Gemini pour générer les réponses. En mode vocal, l’audio est également transmis au service.

## Avant de voyager

Les formalités d’entrée et les conditions de voyage peuvent évoluer. Vérifie les informations relatives aux visas et aux documents nécessaires auprès des ambassades, consulats ou autorités officielles avant ton départ.

## Versions et intégrité des fichiers

Chaque release regroupe l’installateur et les notes de version.

Lorsqu’un fichier `SHA256SUMS.txt` est fourni, tu peux comparer son empreinte avec celle de l’installateur téléchargé grâce à PowerShell.

```powershell
Get-FileHash .\SKAI-Setup-0.1.0-x64.exe -Algorithm SHA256
