[![Build Status](https://app.bitrise.io/app/608515b28f9d4ccd/status.svg?token=4xQGPdkw1fuXzED7xGOC5w&branch=master)](https://app.bitrise.io/app/608515b28f9d4ccd)

# Mascotas

This is an example Android Application that follow up Clean Architecture principles using MVVM pattern with Google architecture components and kotlin.
The application has been made according to https://members.architectcoders.com/ requirements, which are:
* Follow SOLID principles
* Use a presentation pattern (MVP or MVVM).
* Use Google Architecture Components.
* Make a Clean Architecture, similar to Robert C. Martin (Uncle Bob) solution (https://blog.cleancoder.com/uncle-bob/2016/01/04/ALittleArchitecture.html).
* Use a dependency injector (Dagger or Koin).
* Add some unit tests, integration tests, and UI tests.

## Installation
Clone this repository and import into **Android Studio**
```bash
git clone https://github.com/jrodriguezva/Mascotas.git
```
Then, create a new Firebase project https://console.firebase.google.com/ and generate a google-services.json that allows the app to use a Firebase Database.
The downloaded file must be stored inside the app module.

To login into the app, you can create an user account using Firebase or do it just inside the app. It does not need two steeps verification, so you don't need to use your real email account.

Enjoy!

## Maintainers
This project is mantained by:
* [Álvaro Quintana](https://github.com/AlvaroQ)
* [José Manuel Riballo](https://github.com/RiballoJose)
* [Juan Rodríguez](https://github.com/jrodriguezva)

## Contributing

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -m 'Add some feature')
5. Push your branch (git push origin my-new-feature)
6. Create a new Pull Request 

<p align="center">
<img src="https://github.com/AlvaroQ/Mascotas/blob/main/capturas/captura%20login.jpeg" width="250"> 
<img src="https://github.com/AlvaroQ/Mascotas/blob/main/capturas/captura%20listado.jpeg" width="250"> 
<img src="https://github.com/AlvaroQ/Mascotas/blob/main/capturas/captura%20a%C3%B1adir.jpeg" width="250"> 
<img src="https://github.com/AlvaroQ/Mascotas/blob/main/capturas/captura%20perfil.jpeg" width="250"> 
<img src="https://github.com/AlvaroQ/Mascotas/blob/main/capturas/captura%20editar%20perfil.jpeg" width="250"> 
</p>
