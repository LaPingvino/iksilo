Ĉi tie sekvas paŝoj por instali la IME-dosieron en via Linuks-sistemo, konservitaj por se vi tamen iam ankoraŭ bezonus ilin. La nun plej rekomendata metodo estus instali m17n-db per via pakaĵmastrumilo, kiu devus enhavi ĉion tion.

## Dependaĵoj ##

Apud la dosieroj en ĉi tiu pakaĵo, vi bezonos SCIM.
Instalu jenon kaj ĉiujn ceterajn ties dependaĵojn:
  * scim
  * scim-m17n
  * m17n-db
  * scim-gtk2-immodule (Dank'al Antono kaj ash_rabbi. Pro ŝajna eraro en Debian povas esti ke vi bezonas elŝuti kaj instali ĉi tiun aparte...)

## Kiel instali? ##

  * Instalu la supre menciitajn pakaĵojn kaj ties dependaĵojn. (Povas daŭri iom. Almenaŭ per Ubuntu mi estis preta post mallonge, ĉar ĉio troveblas en ĝia pakaĵaro.)
  * Metu la mim-dosierojn kiujn vi volas uzi en /usr/share/m17n aŭ en /usr/local/share/m17n , kiu ajn haveblas en via sistemo. [root-rajtoj necesas]
  * Startu la programon scim kaj agordu ĝin laŭ la sube menciitaj paŝoj por uzi la ĝustas IME-on. Verŝajne vi por tio bezonas plurfoje restarti la sistemon.

## Agordi SCIM por Esperanta tajpado ##

Atentu: Se vi havas la distribuon Ubuntu aŭ simila, povas esti ke la versio SCIM kiun vi povas instali havas eraron, pro kio necesos aldonaj paŝoj. Legu pri tio ĉi tie (Anglalingve). En la plej nova versio de Ubuntu ĉi tiu problemo ŝajnas solvita. La esenco de la paĝo estas ke vi uzu la komandon 'im-switch -z en_US.UTF-8 -c'. Vi en tiu anstataŭu en_US.UTF-8 per via propra lokaĵaro.

  * Startu SCIM per la komando scim. ({Alt+F2} scim {Enigklavo}) 

(Malpli necesaj paŝoj, ja rekomendindaj ĉar alie la programo ŝarĝos ĉiujn enigmetodojn kaj tio povas iom pezi por la sistemo.)

  * Dekstre alklaku la nun aperintan piktogramon de klavaro (tiu estas de SCIM).
  * Elektu SCIM Setup
  * Iru al IMEngine > Global Setup
  * Alklaku Disable All
  * Iru al Other kaj tie elektu la aranĝojn kun eo en la nomo kaj eventuale el aliaj grupoj ĉiujn aliajn enigmetodojn kiujn vi volas uzi. Atentu! Se vi ĉi tie nenion elektas, SCIM ne bone funkcios!
  * Apliku kaj Akceptu 

(Fino de malpli necesaj paŝoj)

  * Restartu la tutan komputilon aŭ la grafikan sistemon ({Ctrl+Alt+Backspace})
  * Provu ĉu funkcias
    * Aktivigu programon en kiu vi povas tajpi.
    * Klaku sur la bildeton de klavaro, tiu troviĝas en la taskopleto.
    * Elektu enigmetodon, ekzemple eo-x-sistemo aŭ eo-plena sub la menuo Other. (Vi povos poste ŝalti aŭ malŝalti la enigmetodon per {Ctrl+Spaco})
    * Tajpu "Eĥoŝanĝo ĉiuĵaŭde" por provi ĉu la ĉapeloj funkcias. 
  * Eventuale ankoraŭfoje restartu la grafikan sistemon ({Ctrl+Alt+Backspace}) aŭ la tutan komputilon se ne funkcias, kaj reprovu. 

Multan plezuron!

-----
Copyright (C) 2007 Joop Kiefte (LaPingvino)

This file is part of the m17n contrib; a sub-part of the m17n
library.

The m17n library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public License
as published by the Free Software Foundation; either version 2.1 of
the License, or (at your option) any later version.

The m17n library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with the m17n library; if not, write to the Free
Software Foundation, Inc., 51 Franklin Street, Fifth Floor,
Boston, MA 02110-1301, USA.
