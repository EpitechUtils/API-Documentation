
# Documentation de l'API [Epitech Intranet]

## Dashboard

### List Dashboard's Projects:
**URL :**  `intra.epitech.eu?format=json`
**METHOD:** `GET`
**OBJECT RETURNED:**`data`

## `data.board.projets`:
```json
[{
	"title": "#OpenSource Project contribution"
	"title_link": "/module/2018/B-INN-000/NCE-0-1/acti-307184/"
	"timeline_start": "03/09/2018, 00:00"
	"timeline_end": "29/06/2019, 01:00"
	"timeline_barre": "56.8053"
	"date_inscription": "29/06/2019, 01:00"
	"id_activite": "307184"
	"soutenance_name": false
	"soutenance_link": false
	"soutenance_date": false
	"soutenance_salle": false
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
```javascript
[{
	"title": "#OpenSource Project contribution"
	"title_link": "/module/2018/B-INN-000/NCE-0-1/acti-307184/"
	"timeline_start": "03/09/2018, 00:00"
	"timeline_end": "29/06/2019, 01:00"
	"timeline_barre": "56.8053"
	"date_inscription": "29/06/2019, 01:00"
	"id_activite": "307184"
	"soutenance_name": false
	"soutenance_link": false
	"soutenance_date": false
	"soutenance_salle": false
}, "..."]
```

This request returns an array of mark data.

#### Fields:

- **`title:`** Project's title 
- **`title_link:`** Url link to concat with base intranet url, used to access project informations.
- **`timeline_*:`** Project's timeline informations (start, end and progress)
- **`date_inscription:`** Project's maximum inscription date
- **`id_activite:`** Project's activity id

## `data.board.activites`:
```json
[{
	"title": "Follow-up - 201yams"
	"module": "B4 - Mathematics"
	"module_link": "/module/2018/B-MAT-400/NCE-4-1/"
	"module_code": "B-MAT-400"
	"title_link": "/module/2018/B-MAT-400/NCE-4-1/acti-322138/"
	"timeline_start": "19/02/2019, 16:30"
	"timeline_end": "19/02/2019, 17:30"
	"timeline_barre": "100.0000"
	"date_inscription": false
	"salle": "Tweet"
	"intervenant": "login@epitech.eu"
	"token": "1"
	"token_link": "/module/2018/B-MAT-400/NCE-4-1/acti-322138/event-330884/token"
	"register_link": "/module/2018/B-MAT-400/NCE-4-1/acti-322138/event-330884/register"
}, ...]
```

This request returns an array of activities data.

## `data.board.modules`:
```json
[{
	"title": "B0 - PCP Development"
	"title_link": "/module/2018/B-PCP-000/NCE-0-1/"
	"timeline_start": "03/09/2018"
	"timeline_end": "14/07/2019"
	"timeline_barre": "54.0992"
	"date_inscription": "22/02/2019, 00:00"
}, ...]
```

This request returns an array of module JSON data.

## `data.board.history`:
```json
[{
	"title": "You can now register to the appointments of the activity : <a href=\"/module/2018/B-NSA-400/NCE-4-1/acti-323094/rdv\">Defense - S.N.A. project</a>"
	"user": {
		"picture": "/file/userprofil/jean.dupond.bmp"
		"title": "Jean Dupond"
		"url": "/user/jean.dupond@epitech.eu/"
	}
	"content": "Remember to register to this appointment.<a href=\"/module/2018/B-NSA-400/NCE-4-1/acti-323094/rdv/\"> See appointments slots ...</a>"
	"date": "2019-02-19 16:51:44"
	"id": "38741929"
	"visible": "1"
	"id_activite": "323094"
	"class": "planification"
}, ...]
```

This request returns an array of history JSON data.

## Profile

## Modules

## Emploi du temps

## Fichiers Intranet
