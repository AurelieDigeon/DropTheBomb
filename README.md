# Happy Places

## Introduction

Création d'une application mobile fun et ludique en 48h lors des [Happy Hacking Days 2014](http://www.happyhackingdays.com/) à la Plaine Images de Tourcoing.
"Drop The Bomb" est un jeu du chat et la souris version 2.0, un joueur peut créer ou rejoindre une partie existante, le but étant de ne pas garder la bombe sur soi et de la jeter à un autre utilisateur proche de soi. Ce jeu a été développé sur Xcode pour iOS 7, il utilise une base de données relationnelle par l'intermédiaire d'une connexion Client/Serveur et un système de géolocalisation.

![Screenshot](screenshots/IMG_0581.png)
## Installation

Nécessite `cocoapods` pour les frameworks externes.

Remplacer dans `NetworkConstants.m` :

```objective-c
NSString* const kGamesListURL = @"http://XXX.XX.XXX.XXX:XXXXX/getGamesList.ashx";
NSString* const kGamesInfosURL = @"http://XXX.XX.XXX.XXX:XXXXX/GameInfo.ashx";
NSString* const kConnectURL = @"http://XXX.XX.XXX.XXX:XXXXX/UserConnect.ashx";
NSString* const kJoinURL = @"http://XXX.XX.XXX.XXX:XXXXX/JoinGame.ashx";
NSString* const kUpdateUserInfosUrl = @"http://XXX.XX.XXX.XXX:XXXXX/UpdateUserInfos.ashx";
NSString* const kBombingUrl = @"http://XXX.XX.XXX.XXX:XXXXX/Bomb.ashx";
NSString* const kCreateUrl = @"http://XXX.XX.XXX.XXX:XXXXX/CreateGame.ashx";
NSString* const kGameOver = @"http://XXX.XX.XXX.XXX:XXXXX/Gameover.ashx";
```

Par le reseau correspondant.

## Licence

```
Copyright 2013 Aurélie Digeon, Alain Galas, Alison Harlé, Laurent Thiebault, Loïc Vanderschooten, Charles-Henri Dumalin, Guillaume Bisiaux et Mustafa Nezzari

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
