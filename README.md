# Suivi des archimonstres du Dofus ocre

Page pour suivre les 286 archimonstres des étapes 4 à 18 de la quête du Dofus ocre, L'éternelle moisson.

Ouvre `archimonstres.html` dans ton navigateur, avec un double-clic.

## Sauvegarder son avancée

Les coches restent dans le navigateur, sur cet ordinateur. Elles ne sont pas écrites dans un fichier toutes seules. Si tu changes de navigateur, d'ordinateur, ou si les données du site sont effacées, la progression disparaît.

Pour garder une copie :

1. Clique sur **Exporter**. Le navigateur télécharge `archimonstres.txt`, en général dans Téléchargements.
2. Range ce fichier où tu veux. Le déposer à côté de la page est pratique, et Git l'ignore.
3. Exporte souvent, après une session de captures.

Pour reprendre une sauvegarde, clique sur **Importer** et choisis le fichier. Les coches affichées deviennent celles du fichier, puis elles sont de nouveau gardées dans le navigateur.

Le fichier contient une ligne par archimonstre. `1` signifie capturé, `0` signifie pas encore. Le nom suit une tabulation.

```
# 1 = capturé, 0 = pas encore. Une ligne par archimonstre.
1	Sousourizoto le Collant
0	Arachitik la Souffreteuse
```

## La page

En haut, le compteur indique combien d'archimonstres sont capturés, combien restent, et le pourcentage. **Sauvegarde** propose **Exporter** et **Importer**.

Les pastilles d'étapes, de 4 à 18, filtrent la quête. Chacune montre les captures de l'étape, par exemple `3/20`. **Toutes** réaffiche la liste complète.

La recherche accepte un nom d'archimonstre, une zone, un lieu ou le monstre de base. Les autres filtres se combinent avec elle :

- **Lieu** ne garde qu'un endroit de spawn.
- **Statut** affiche tout, seulement les archimonstres pas encore capturés, ou seulement ceux déjà capturés.
- **Niveau entre** garde ceux dont la fourchette de niveau croise l'intervalle saisi.
- **Effacer les filtres** remet la liste entière.

## Le tableau

Une ligne égale un archimonstre. Cliquer sur la ligne coche ou décoche la capture.

| Colonne | Contenu |
| --- | --- |
| Capturé | Case cochée si l'archimonstre est déjà pris |
| Archimonstre | Nom, portrait et monstre de base |
| Étape | Étape de la quête, de 4 à 18 |
| Zone | Région, par exemple Amakna ou Astrub. Plusieurs régions sont séparées par un point médian |
| Lieu | Endroit précis où le trouver |
| Niv. min / Niv. max | Fourchette de niveau du monstre de base |

Le portrait est celui du monstre de base. Un clic sur un titre de colonne trie la liste. Un second clic inverse l'ordre.

**Tout décocher**, en bas de page, enlève toutes les coches après confirmation.
