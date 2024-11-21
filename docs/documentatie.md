---
layout: page-with-side-nav
title: Documentatie RGBZ
folder_files:
  - title: RGB Zaken 1 0 (in gebruik) 201000922 (pdf)
    path: documenten/RGB_Zaken_1 0_(in_gebruik)_201000922.pdf
    group: 10
    versie: 1.0
    status: Definitief
    omschrijving: Informatiemodel Zaken (RGBZ) v1.0
    datum: 22-09-2010
  - title: RGB Zaken 1.0 (in gebruik) (zip)
    path: documenten/RGB_Zaken_1.0_(in_gebruik).zip
    group: 10
    versie: 1.0
    status: Definitief
    omschrijving: 
    datum: 22-09-2010
  - title: RGB Zaken 1.0 schemas juni 2010 (zip)
    path: documenten/RGB_Zaken_1.0_schemas_juni_2010.zip
    group: 10
    versie: 1.0
    status: Definitief
    omschrijving: Schema's informatiemodel Zaken (RGBZ) v1.0
    datum: juni 2010
  - title: RGB Zaken Verantwoording 20100922 (pdf)
    path: documenten/RGB_Zaken_Verantwoording_20100922.pdf
    group: 10
    versie: 1.0
    status: Definitief
    omschrijving: Verantwoording tot stand koming informatiemodel Zaken (RGBZ) v1.0
    datum: 22-09-2010
  - title: RGBZ 01.00 in gebruik UML (EAP) (zip)
    path: documenten/RGBZ_01.00_in_gebruik.zip
    group: 10
    versie: 1.0
    status: Definitief
    omschrijving: Informatiemodel RGBZ 01.00 _ UML (EAP)
    datum: 22-09-2010
  - title: RGBZ domeintabellen 1.0 (zip)
    path: documenten/RGBZ_domeintabellen_1.0.zip
    group: 10
    versie: 1.0
    status: Definitief
    omschrijving: Tabellen met domeinwaarden van attributen in het Informatiemodel Zaken (RGBZ) v1.0
    datum: 22-09-2010
  - title: RGBZ 2.0 deel 1 (CONCEPT) (pdf)
    path: documenten/GEMMA_RGBZ_2.0_deel_1_CONCEPT3_20141204.pdf
    group: 20
    versie: 3e concept 2.0
    status: 
    omschrijving: 3e concept versie RGBZ 2.0 deel 1
    datum: 04-12-2014
  - title: RGBZ 2.0 deel 2 (CONCEPT) (pdf)
    path: documenten/GEMMA_RGBZ_2.0_deel_2_CONCEPT3_20141204.pdf
    group: 20
    versie: 3e concept 2.0
    status: 
    omschrijving: 3e concept versie RGBZ 2.0 deel 2
    datum: 04-12-2014
---

# Documentatie

## RGBZ 1.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 10 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
