# bailly-api

> [!NOTE]
> Ce dépôt contient uniquement l'API de l'application Bailly. Le client se trouve quant
à lui dans le dépôt principal ([bailly.app](https://github.com/antoineboquet/bailly.app)).

Veuillez noter que la base de données utilisée par l'API n'est PAS distribuée avec le
code. Si vous cherchez à faire fonctionner cette API par vous-même, vous devrez au
préalable convertir les données du [Bailly 2020 Hugo Chávez](http://gerardgreco.free.fr/spip.php?article24) dans le format
spécifié dans le code source.

## Licence

Copyright (C) 2021-2026 Antoine Boquet, Benjamin Georges

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see https://www.gnu.org/licenses/agpl-3.0.fr.html.

### Données

Cette application utilise les données du [Bailly 2020 Hugo Chávez](http://gerardgreco.free.fr/spip.php?article24) (Gérard Gréco,
André Charbonnet, Mark De Wilde, Bernard Maréchal _et al._), distribuées sous licence
_Creative Commons Attribution - Pas d'Utilisation Commerciale - Pas de Modification_
(CC&nbsp;BY-NC-ND&nbsp;4.0).

### Analyse morphologique

Cette application utilise [libmorpheus](https://github.com/defense-humanites/libmorpheus),
qui modernise et étend les capacités de l'analyseur morphologique Morpheus, lequel a
initialement été développé dans le cadre de la Perseus Digital Library (Gregory Crane
_et al._ pour le compte de l'université Tufts). `libmorpheus` est distribuée sous licence
mixte, MPL-2.0 et AGPL-3.0-or-later.