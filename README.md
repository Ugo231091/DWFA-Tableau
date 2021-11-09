# DWFA-Tableau

<p align="center">
  <img src="images/Images/DWFA.png"/>
</p>

DWFA (Drinking Water For All)  présente 3 domaines d’expertises :
* Création de services d’accès à l’eau potable ;
* Modernisation de services d’accès à l’eau déjà existants ;
* Consulting auprès d’administrations/gouvernements à propos des politiques d’accès à l’eau.
L’association a effectué une demande de financement auprès d’un bailleur de fonds en présentant ces
3 domaines d’expertise.

Ces nouveaux financements, s’ils sont accordés par le bailleur, pourront permettre d’investir dans un
des domaines d’expertise dans un pays qui n’est pas encore déterminé.
Dans ce cadre, vous êtes missionné pour réaliser un dashboard présentant une vue globale de l’accès à
l’eau potable dans le monde. Celui-ci permettra de choisir le pays à cibler dès que le bailleur de fonds
aura donné sa réponse sur le domaine d’expertise qu’il souhaite financer.

## Besoins pour l’histoire Tableau

3 vues sont demandées sur l’histoire Tableau à créer avec tous les
indicateurs choisis sur chaque vue :
* une vue mondiale avec une agrégation des indicateurs au niveau
mondiale ;
* une vue continentale avec les indicateurs agrégés pour le continent
sélectionné par l’utilisateur ;
* une vue nationale avec les indicateurs pour le pays sélectionné par
l’utilisateur.

## Indicateurs à utiliser

Quelques indicateurs à suivre ont été mentionnés durant la réunion. Ce ne
sont que des exemples d’indicateurs utilisés par le passé, d’autres
indicateurs pourront être utilisés :
* le taux de mortalité dû à de l’eau insalubre ;
* la population / densité de population ;
* la part d’habitants ayant accès à l’eau potable ;
* la stabilité politique du pays.
* l’évolution de ces facteurs dans le temps.

Besoin d’indicateurs calculés à l’échelle nationale pour les 3 domaines
d’expertise :
* Domaine 1 (création de services) : graphique combinant le taux
d’accès à l’eau potable et le taux de population urbaine.

* Domaine 2 (modernisation des services) : Besoin d’un graphique
qui combine le taux de services (d’infrastructures) “basiques” et le
taux d’infrastructures de qualité (qualifiées comme “safely managed”
dans les données) afin d’identifier les pays qui ont un gros besoin
d’améliorer la qualité de leurs services
* Domaine 3 (consulting) : Besoin d’un graphique combinant
l’efficacité de la politique gouvernementale d’accès à l’eau (politique
efficace

## Précisions techniques

Les précisions techniques qui ont été discutées et validées :
* Pour pouvoir exclure les pays dont l’instabilité politique est trop
forte, il faudrait que le tableau de bord inclue un filtre (modifiable par
l’utilisateur) pour exclure les pays trop instables.
* Pour les indicateurs combinant 2 variables, il faudrait afficher un
nuage de points.
* Il est important de voir l’évolution de certains indicateurs dans le
temps.
* La palette « Bleu », en cohérence avec la couleur de l’eau, devra être
utilisée sur Tableau.
