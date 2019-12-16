# notebook.csharp
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Enriquecerviro/notebook.csharp/master?urlpath=lab)
## Cómo funciona?
A grander rasgos funciona tal que yo me descargo el repositorio lo modifico y después de hacer push esos cambios ya se reflejan cuando lo abra en remoto a través de Binder.

> LOCAL
(Tenemos que tener instalados los cuadernos jupyter y habilitado el kernel de C# Y F#).
En local simplemente trabajamos lo que necesitamos y luego subimos al repositorio.

> REMOTO
Siempre que se actualize el repo con nuevos cuadernos o lecciones, si se abre desde Binder gracias al DockerFile va a leer el repo y colocer los archivos que hay dónde pueda leerlos.

