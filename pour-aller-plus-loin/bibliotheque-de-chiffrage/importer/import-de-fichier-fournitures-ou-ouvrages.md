# Import de fichier fournitures ou ouvrages

Vous pouvez importer un fichier de fournitures ou d'ouvrages en provenance d'un autre logiciel, ou de Excel par exemple.

{% hint style="info" %}
Pour importer un tarif fournisseur, [consultez cette page](import-de-tarifs-fournisseurs.md).
{% endhint %}

## Etape 1 - Préparez votre fichier



⚠ Le fichier doit être au format Excel \(.xlsx\), ou csv \(.csv\)

1 Ouvrez le fichier dans votre tableur

2 Vérifiez que la première ligne contient les titres de colonnes, ce sera plus pratique lors de l'importation. Par exemple :

| **Identifiant \(code article\)** | **Libellé \(désignation\)** | **Unité** | **Prix d'achat** | **Prix de vente** | ... |
| :--- | :--- | :--- | :--- | :--- | :--- |
| MEP Porte | Mise en peinture de porte | M² | 14,99 | 21,55 | ... |

3 Vérifiez ensuite les points suivants :

* Chaque ligne du fichier doit contenir un article \(ou un ouvrage\)
* Aucune ligne ne doit être vide
* Il ne doit pas y avoir 2 \(ou plusieurs\) fois le même identifiant \(code\) article dans le fichier
* Les colonnes contenant des valeurs \(prix\) doivent être au **format nombre**, et ne contenir aucun symbole monétaire :

  ![](../../../.gitbook/assets/screenshot-110c-.png) 1234.56

  ![](../../../.gitbook/assets/screenshot-110c-.png) 1234.567

  ![](../../../.gitbook/assets/screenshot-110c-.png) 1234,56

  ![](../../../.gitbook/assets/screenshot-110c-.png) 1 234.56

  ![](../../../.gitbook/assets/screenshot-110d-.png) 1 234.56 **€**

  \*\*\*\*![](../../../.gitbook/assets/screenshot-110d-.png) **€** 1234.56

{% hint style="info" %}
* Si vos articles ou ouvrages n'ont pas d'identifiant, un identifiant sera automatiquement créé par le logiciel
* Si la colonne "Prix de vente" est absente ou vide, un prix sera calculé en appliquant la marge que vous avez définie dans vos paramètres "Entreprise"
* Si la colonne "Taux de TVA" est absente ou vide, c'est le taux de TVA sur achats par défaut qui sera appliqué \(20% pour la France\) _Le taux de TVA n'est pas appliqué aux ouvrages, car il est défini au niveau du devis_
* Si les colonnes "Compte de vente" et "Compte d'achat" sont vides, c'est votre [paramétrage comptable ](../../exports-comptables/parametrage-1/)qui s'appliquera
{% endhint %}

4 __Après avoir vérifié votre fichier, enregistrez-le.



## Etape 2 - Importez votre fichier



1 Ouvrez le menu "Bibliothèque &gt; Importer", et sélectionnez le type : Fournitures ou Ouvrages

Ou bien directement depuis votre bibliothèque d'éléments / d'ouvrages, cliquez sur le bouton "Importer des fournitures" ou "Importer des ouvrages"

![](../../../.gitbook/assets/capture%20%2821%29.png)

2 Recherchez votre fichier \(au format .xlsx ou .csv\)

3 Précisez si la première ligne de votre fichier contient des titres \(conseillé\)

_Généralement, vous n'avez pas à modifier le séparateur et l'encodage du fichier, sauf éventuellement si le fichier est issu d'un logiciel américain._

4 Cliquez sur "Analyser le fichier"

5 Faites correspondre les colonnes disponibles \(colonne de gauche\) avec les colonnes de votre fichier

![](../../../.gitbook/assets/capture%20%288%29.png)

6 Cliquez sur le bouton "Suivant"

7 Après vérification des données, Importez le fichier.



## Mise à jour de vos prix

Il est parfois plus facile de réaliser une mise à jour de vos prix "en masse" sur Excel, que un par un dans le logiciel.



1 Exportez la liste de vos articles ou de vos ouvrages, depuis la liste, ou depuis le menu "Gestion &gt; Exporter mes données"

2 Ouvrez le fichier extrait dans Excel

3 Mettez à jour vos prix dans Excel

4 Vérifiez votre fichier

5 Réimportez le fichier dans le logiciel pour réaliser une mise jour automatique.

