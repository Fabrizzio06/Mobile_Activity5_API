
Activity5API

App de iOS hecha con SwiftUI que muestra personajes de Rick and Morty obtenidos de una API publica.

Que hace la app

Muestra una lista de personajes con su imagen, nombre, especie, genero y estatus. Al tocar un personaje se abre una pantalla de detalle con su origen, ultima ubicacion y numero de episodios.

Incluye indicador de carga y mensajes de error (sin conexion, error del servidor u otros fallos) con un boton para volver a intentar.

API

Rick and Morty API: https://rickandmortyapi.com/

Endpoint usado: https://rickandmortyapi.com/api/character

Estructura (MVVM)
Character.swift: modelos (Model)
CharacterViewModel.swift: logica y estados de carga/error (ViewModel)
ContentView.swift: lista y navegacion (View)
CharacterListRowView.swift: fila de la lista (View)
CharacterDetailView.swift: pantalla de detalle (View)
MyApp.swift: punto de entrada
Como ejecutar

Requisitos: Xcode 27 y iOS 27.0 como target (configurado en el proyecto).

Clonar el repositorio.
Abrir Activity5API.xcodeproj en Xcode.
Elegir un simulador de iPhone.
Presionar Cmd + R.

Autor

Fabrizzio Emanuel Mariano Arango
Activity5API.zip

ZIP
