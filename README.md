<img src="https://blog.bracketshow.com/wp-content/uploads/2021/07/csharp.png" width="100px">

# ML.Net Getting started tuto 

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)]()
[![forthebadge](https://forthebadge.com/images/badges/made-with-c-sharp.svg)](https://forthebadge.com)

[![Generic badge](https://img.shields.io/badge/For-Training-<green>.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/Only-Terminal-<green>.svg)](https://shields.io/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)]()

</br>
https://dotnet.microsoft.com/en-us/learn/ml-dotnet/get-started-tutorial/intro

## Scénario 

Une application qui permet de connaître le sentiment d'un retour client. ( Positif - Négatif )
</br>
<b>Algrithme :</b> classification

## Installation

```
$ git clone git@github.com:BoisselNicolas/ML.NET-GetStarted.git
```

## Usage 

Dans le fichier "consumeModelApp/Program.cs"

Saisissez une donnée d'entrée dans la partie 

```
var input = new ModelInput()
            {
              Col0 = "I love it" //<-- séléctionnez la donnée d'entrée
            };
```

Pour éxécuter le programme

```
$ cd consumeModelApp
$ dotnet run 
```

## Résultat

Le programme nous retourne le sentiment de la phrase d'entrée

``` 
Text: I love it
Sentiment: Positive
```

## Versions

**Dev :** 1.0


## Auteurs

* **BOISSEL Nicolas** 
