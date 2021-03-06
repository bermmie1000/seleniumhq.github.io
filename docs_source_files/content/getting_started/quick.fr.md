---
title: "Tour rapide"
weight: 1
---

Selenium n'est pas juste un outil ou une API
mais est composé de nombreux outils.

## WebDriver

Si vous débutez dans l'automatisation de test de site web _desktop_ 
vous allez utiliser les APIs WebDriver. _[WebDriver]({{< ref "/webdriver/_index.md" >}})_ utilise 
les APIs d'automatisation fournies par les distributeurs de navigateur 
pour les contrôler et exécuter les tests. 
C'est comme si un utilisateur réel utilisait le navigateur. 
Puisque WebDriver n'a pas besoin que ses APIs soient compilées avec le code de l'application testée,
il est non intrusif par nature. Ainsi vous testez exactement l'application qui sera en production.

## IDE

_[IDE](https://selenium.dev/selenium-ide)_ (Integrated Development Environment) 
est l'outil que vous utilisez pour développer vos cas de test Selenium. Il s'agit d'un Chrome facile à utiliser
et l'extension Firefox et est généralement le moyen le plus efficace de développer
cas de test. Il enregistre pour vous les actions des utilisateurs dans le navigateur, en utilisant
commandes Selenium existantes, avec des paramètres définis par le contexte de
cet élément. Ce n'est pas seulement un gain de temps, mais aussi un excellent moyen
d'apprentissage de la syntaxe du script Selenium.


## Grid

Selenium Grid allows you to run test cases in different 
machines across different platforms. The control of 
triggering the test cases is on the local end, and 
when the test cases are triggered, they are automatically 
executed by the remote end.

After the development of the WebDriver tests, you may face 
the need of running your tests on multiple browser and 
operating system combinations.
This is where _[Grid]({{< ref "/grid/_index.md" >}})_ comes into the picture.