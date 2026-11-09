# Proyecto-1-Buscador-paises
proyecto sobre crear una pagina a traves de la informacion de una api

## Ficha descriptiva de la API

Consiste en escribir un texto breve respondiendo a estas preguntas sobre la API que hemos elegido (REST Countries):

    Nombre de la API: REST Countries

    Categoría en Public APIs: Content / Geography (o World)

    Quién la mantiene: Proyecto Open Source mantenido por la comunidad.

    Dónde está su documentación: [https://restcountries.com/](https://restcountries.com/)

    Condiciones de uso y licencia: Es gratuita, no requiere clave (Auth: No), usa HTTPS: Yes y sus datos son de acceso libre (Open Data / Licencia MIT).

    Peticiones realizadas al siguiente endpoint https://api.restcountries.com/countries/v5.

## Tabla de los campos

| Campo del JSON| Tipo | Qué es para el lector |
| --- | --- | --- |
| names.common | texto | El nombre de cada país |
| flag | lista de objetos | Es una lista donde dentro tiene diferente informacion sobre la bandera como una url, el emoji...|
| flag.url_png | url | es la url de cada bandera que tiene |
| population | numero | el numero de habitantes |
| borders | lista | ees una lista de los paiases con los que tiene frontera |

## Paginas

Index es la pagina de inicio de la web donde te cuenta un poco sobree que va la web y te muestra los sitios destacados el paln seria en como ir cambiando esos sitios destacados cada semana o algo asi. Y dude sobre si en pj, en capital poner con strong o no pq despues se va a poder modelar con html pero al final lo deje.

El catalogo es una pagina dedicada a poner contenido de ciertos paises pero un poco y separado por regiones.

comparativa es sobre coger ciertos paises y compararlos con una tabla hat lo unico que dude un poco fue sobre el diseño de la tabla.

propuesta es sobre hacer un formulario de donde el usuario quiere viajar y te pide diferentes campos como datos personales, la planificacion, datos del destinos y que ponga una url/foto del destino y que escriba un texto sobre el destino.

sobre los datos es basicamente informar de que api he savado los datos y como los he utilizado.