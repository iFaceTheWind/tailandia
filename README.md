# Tailandia · A tu aire

Una guía visual con recomendaciones personales, naturaleza, comida y opciones para viajar en diciembre. Sin itinerario cerrado.

- **Destinos:** Bangkok, mar/sur, norte y rutas conocidas. Vistas Mapa y Cuaderno.
- **Platos de comida:** once platos, explicados en una o dos frases, con enlaces para probarlos.
- **Consejos:** Grab, pedir sin picante, curiosidades y el bloque «Mejor evitar».

Incluye 41 fichas y 21 fotografías con créditos. La sección norte enlaza a Somos Tailandia, una agencia con la que trabajó el autor. Las experiencias propias se distinguen de los recuerdos probables y de las zonas aún no visitadas.

## Abrir

`index.html` incluye el código, los datos y las fotografías. Puedes abrirlo en un navegador, o servir la carpeta desde el terminal:

```sh
python -m http.server 8000
```

Después abre `http://localhost:8000`. Las calles de OpenStreetMap, Google Maps y las fuentes externas necesitan internet; hay un plano esquemático disponible sin teselas.

[Site alojado](https://tailandia-a-tu-aire.iface.chatgpt.site) — acceso privado del propietario. Este repositorio conserva la guía y su fuente editable; subir cambios aquí no actualiza automáticamente ese Site.

## Editar y reconstruir

Los textos y datos están en `source/build-v2.py`; el diseño y la navegación, en `source/guide-v2.template.html`. Para generar el HTML tras editar, usa Python 3.9 o posterior, sin instalar dependencias:

```sh
python source/build-v2.py
```

La salida actualiza `index.html` y `source/content-v2.json`. Las fotografías, créditos y Leaflet están incluidos en `source/`.

## Fuentes y licencias

Las referencias y los créditos de la foto se consultan al abrir las fichas de los lugares. Las fotos de Wikimedia Commons tienen sus licencias individuales; algunas imágenes ilustran platos o entornos, y se indica en las fichas. Leaflet conserva su licencia en `source/vendor/leaflet-license.txt`.

Las condiciones de transporte, precios, horarios y clima pueden cambiar. Los ejemplos económicos son orientativos y los patrones de diciembre no son un pronóstico.
