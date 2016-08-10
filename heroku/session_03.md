### Porque Heroku
- Deploy instantaneamente con "git push"
- Add-on resources (aplicaciones, bases de datos, etc.)
- Aislamiento. Su un proceso muere, heroku lo reinicia. Sin afectar a toda la aplicación.
- Logging y visibilidad
- Escala procesos facilmente.

#### Escalabilidad
Los procesos que corren en tu instancia se llaman Dynos.
Workers para realizar tareas en background.

Estos Dynos pueden escalarse de forma horizontal, añadiendo más dynos. O bien de forma vertical añadiendo más recursos de memoria y CPU al Dyno.
Un Dyno tiene 512Mb de Ram y 1024 de Swap y un CPU de 4 Cores.


#### Escalabilidad elastica.
Heroku toma los recursos que necesitas, unicamente cuando los necesitas.

#### Escalabilidad on demand.
Entre más demanda tengas, predeterminada por el usuario.

### Addons.
https://addons.heroku.com

Ejemplo. New Relic.
Permite tener una idea de la aplicación sobre escalabilidad, rendmiento, eficiencia, trafico, cuellos de botella, todo el perfomance. Ralizando un diagnostico.






