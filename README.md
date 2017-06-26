# Ezo - Le Defi Code
Ce dépôt Git est destiné aux candidats désirant obtenir une entrevue pour un poste d'expert-conseils en développement logiciel chez Ezo. Si vous n'avez pas été en contact avec notre équipe de recrutement, veuillez envoyer un courriel à recrutement@ezoqc.com.

## Le défi
Le défi consiste à une épreuve de code golf. Ces exercices servent aux programmeurs de bac à sable pour s'amuser à développer en essayant d'appliquer de nouvelles connaissances. Ce défi évoluera au fil du temps en offrant aux candidats de nouveaux code golf à essayer.

### Code Golf: Calculatrice par chaîne de caractères
Vous devez créer une application qui évalue une chaîne de caractères, comme si elle avait été entrée dans une calculatrice. Votre programme doit accepter une entrée et produire une réponse juste en sortie.

#### Réglements

Le programme doit:
* Être écrit dans le langage orienté-objet de votre choix
* Authoriser les nombres à virgule flotante et les nombres négatifs
* Supporter ''au moins'' les opérateurs de base (+, -, * et /)
* Supporter un ou plusieurs espaces entre les opérateurs et les nombres
* Respecter la priorité des opérateurs
* Avoir un code propre qui respecte les principes de programmation OO

Vous ne pouvez pas:
* Copier du code sur Internet
* Utiliser du code produit par quelqu'un d'autre

#### Processus d'évaluation
Dès que vous recevez le courriel d'invitation au défi code, ''vous disposez de 14 jours'' pour produire le programme. Lorsque vous serez satisfait de votre code, vous allez être invité à présenter votre programme, son design et son architecture à nos évaluateurs. Prévoyez une présentation d'environ 1h.

Notez que vous ne serez pas évalué sur la quantité de fonctionnalités implémentées ou sur un code fonctionnel à 100%. Nous cherchons à comprendre votre mentalité par rapport à l'éxercice, vos choix et leurs raisons, le côté créatif de votre code, vos aptitudes à bien faire comprendre votre code, etc.. Si "1+1" retourne "4", vous ne serez pas pénalisé si vous pouvez expliquer pourquoi.

#### Nos cas de test
| Test     | Résultat attendu |
|----------|-----------------:|
| "1+1"    | "1"              |
| "1 + 2"  | "3"              |
|"1 + -1"  | "0"              |
|"-1 - -1" | "0"              |
| "5-4"    | "1"              |
| "5\*2"   | "10"             |
|"(2+5)\*3"| "21"             |
| "10/2"   | "5"              |
|"2+2\*5+5"| "17"             |
|"2.8\*3-1"| "7.4"            |
|"2^8"     | "256"            |
|"2^8\*5-1"| "1279"           |
|"sqrt(4)" | "2"              |
|"1/0"     | Erreur\*         |

Note: D'autres cas de test peuvent être utilisés. Vous ne devez pas implémenter tous les opérations du tableau ci-dessus. Vous pouvez simplement expliquer comment vous auriez implémenté les opérateurs manquants.

#### Limitation
* L'architecture doit être belle et propre
* Le code doit être beau et propre

Lorsque vous avez terminé, veuillez rendre votre code disponible à l'équipe de recrutement par le moyen qui vous convient le mieux. Nous vous recommendons un dépôt Git public sur GitHub.

Sur ce, bon code!
