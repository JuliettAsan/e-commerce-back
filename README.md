## explora-gestor-eventos-back

## ✅ GET /events

Obtiene una lista de eventos, permite filtrar por date o name, ademas de cambiar el offset y page por queryParams

Ejemplos:

/events?page=1&offset=8

/events?page=1&name=Astros

/events?page=1&offset=5&name=Astros&date=2023-11-09T16:23:11.313Z


## ✅ POST /events

Crea un nuevo evento. Debe contener los campos obligatorios.

## ✅ GET /events/{id}

Obtiene un evento por su id

## ✅ PUT /events/{id}

Actualiza un evento por si id

## ✅ DELETE /events/{id}

Elimina un evento por su id


## Para realizar las peticiones se debe tener en cuenta la lista de propiedades obligatorias y opcionales:

## Propiedades obligatorias:

```json

{
  "name": "",
  "owner": " ",
  "type": " ",
  "programs": " ",
  "startDate": " ",
  "endDate": " ",
  "responsable": " ",
  "sponsor": " ",
  "format": " ",
  "space": " "
}
```

## Propiedades opcionales:

```json
{
  "location": " ",
  "audience": " ",
  "youtubeLink": " ",
  "guest": " ",
  "modality": " ",
  "community": " ",
  "ticketsType": " ",
  "topic1": " ",
  "topic2": " ",
  "assistants": " ",
  "facebookLink": " ",
  "instagramLink": " ",
  "comment": " ",
  "deia": " "
}
```