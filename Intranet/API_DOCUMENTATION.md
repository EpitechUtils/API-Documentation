# Documentation de l'API [Epitech Intranet]

## Dashboard

### List Dashboard's Projects:
**URL :**  `intra.epitech.eu?format=json`
**METHOD:** `GET`
**OBJECT RETURNED:** `data`

## `data.board.projets`:
```json
[{
	"title": "#OpenSource Project contribution",
	"title_link": "/module/2018/B-INN-000/NCE-0-1/acti-307184/",
	"timeline_start": "03/09/2018, 00:00",
	"timeline_end": "29/06/2019, 01:00",
	"timeline_barre": "56.8053",
	"date_inscription": "29/06/2019, 01:00",
	"id_activite": "307184",
	"soutenance_name": false,
	"soutenance_link": false,
	"soutenance_date": false,
	"soutenance_salle": false,
}, ...]
```

This request returns an array of project data.

#### Fields:

- **`title:`** Project's title 
- **`title_link:`** Url link to concat with base intranet url, used to access project informations.
- **`timeline_*:`** Project's timeline informations (start, end and progress)
- **`date_inscription:`** Project's maximum inscription date
- **`id_activite:`** Project's activity id

## `data.board.notes`:
```json
[{

    "title": "Follow-up - Something",
    "title_link": "/module/2019/B-DEV-510/NCE-5-1/acti-367222/",
    "note": "50",
    "noteur": "jean.dupont@epitech.eu"            
}, ...]
```

This request returns an array of mark data.

## `data.board.activites`:
```json
[{

    "title": "Bootstrap - 309pollution",
    "module": "B5 - Mathematics",
    "module_link": "/module/2019/B-MAT-500/NCE-5-1/",
    "module_code": "B-MAT-500",
    "title_link": "/module/2019/B-MAT-500/NCE-5-1/acti-356983/",
    "timeline_start": "28/01/2020, 10h30",
    "timeline_end": "28/01/2020, 12h00",
    "timeline_barre": "0.0000",
    "date_inscription": "27/01/2020, 10h30",
    "salle": "Qwant",
    "intervenant": "jean.dupont@epitech.eu",
    "token": null,
    "token_link": "/module/2019/B-MAT-500/NCE-5-1/acti-356983/event-374779/token",
    "register_link": "/module/2019/B-MAT-500/NCE-5-1/acti-356983/event-374779/register"           
}, ...]
```

This request returns an array of activities data.

## `data.board.modules`:
```json
[{
    "title": "G0 - Epitech JAM",
    "title_link": "/module/2019/G-JAM-001/NCE-0-1/",
    "timeline_start": "02/09/2019",
    "timeline_end": "01/03/2020",
    "timeline_barre": "80.4462",
    "date_inscription": "09/02/2020, 00h00"            
}, ...]
```

This request returns an array of module JSON data.

## `data.board.history`:
```json
[{
	"title": "You can now register to the appointments of the activity : <a href="/module/2018/B-NSA-400/NCE-4-1/acti-323094/rdv">Defense - S.N.A. project</a>",
	"user": {
		"picture": "/file/userprofil/jean.dupond.bmp",
		"title": "Jean Dupond",
		"url": "/user/jean.dupond@epitech.eu/",
	}
	"content": "Remember to register to this appointment.<a href="/module/2018/B-NSA-400/NCE-4-1/acti-323094/rdv/"> See appointments slots ...</a>",
	"date": "2019-02-19 16:51:44",
	"id": "38741929",
	"visible": "1",
	"id_activite": "323094",
	"class": "planification"
}, ...]
```

This request returns an array of history JSON data.

## Profile

## Modules

## Emploi du temps

## Fichiers Intranet

