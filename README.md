### Hola, soy Matt

Dev de Buenos Aires. Me gusta tocar backend y mobile en el mismo
proyecto para no aburrirme, y aprender cosas nuevas sin preguntarle
a nadie primero.

Ultimamente ando metido en un side project que mezcla salud y plata
personal, usando Go, Flutter y Next.js. Pronto subo mas detalle.

Si queres charlar sobre backend, apps o cualquier bardo tecnico,
escribime.

---

### Proyectos

Pulso es mi side project actual. Son tres repos que se hablan entre
ellos: API, mobile y web. La idea es llevar registro de peso y
gastos en el mismo lugar, porque los dos cuestan igual de poco
cuando uno los deja crecer.

**[pulso-api](https://github.com/MatiasHernanSerrato/pulso-api)**
Backend en Go 1.23 con GraphQL (gqlgen), Postgres + TimescaleDB,
JWT y metricas con OpenTelemetry. Tiene detector de anomalias
basico (z-score) para avisar cuando algo se dispara en el peso o en
los gastos.

**[pulso-mobile](https://github.com/MatiasHernanSerrato/pulso-mobile)**
App en Flutter 3.24, offline-first con Drift. Se conecta por BLE a
balanzas con el perfil estandar 0x181D (Weight Scale) asi que
anda con cualquier balanza decente, no solo las que piden una app
propia. Shorebird para OTA.

**[pulso-web](https://github.com/MatiasHernanSerrato/pulso-web)**
Dashboard en Next.js 15 (App Router + RSC) con Tailwind y Visx para
los graficos. Mismos datos que la app mobile pero pensado para
mirar en la compu mientras tomas mate.
