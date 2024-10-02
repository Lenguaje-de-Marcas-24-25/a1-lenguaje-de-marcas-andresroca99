## Indica qué es un lenguaje de marcas
Un lenguaje de marca NO es un lenguaje de programación, aunque se llame también
lenguajes. De hecho, no debemos utilizar la palabra programar cuando nos referimos a la
confección de documentos electrónicos mediante LM, de igual forma que tampoco nos
referimos a programar cuando creamos un documento electrónico con un procesador de
textos.
## Características generales de los lenguajes de marcas.
### Texto plano
### Compactibilidad
### Independencia del dispositivo final
### Especialización
### Flexibilidad
## Clasifica los lenguajes de marcas e identifica los más relevantes.
### De presentación
Los procesadores de texto y en general las aplicaciones de edición
profesional utilizan este tipo de marcado, como por ejemplo RTF y TeX
### Descriptivo, estructural o semántico
XML es un metalenguaje expresamente diseñado para generar marcado descriptivo y
los lenguajes derivados de XML con este propósito son: EBML, RDF, XFML, OWL y XTM.
### Híbrido
Lenguajes que contienen marcas de los dos tipos anteriores indistintamente. Por
ejemplo HTML
## Indica los distintos ámbitos de aplicación de los lenguajes de marcas.
### Desarrollo web
### Ámbito científico
### Gráficos vectoriales
### Metainformación
### Bases de datos
### Intercambio de información
### Mensajería
## Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:
### HTML <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sample HTML Page</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a sample paragraph in HTML.</p>
</body>
</html>
HTML es el lenguaje de marcado estándar para crear páginas web. Utiliza una estructura jerárquica de etiquetas (elementos) como <html>, <head>, <body>, entre otras. Estas etiquetas definen la estructura y el contenido de una página web.

### iCalendarBEGIN:VCALENDAR
VERSION:2.0
BEGIN:VEVENT
UID:uid1@example.com
DTSTAMP:20231001T090000Z
DTSTART:20231005T100000Z
DTEND:20231005T110000Z
SUMMARY:Meeting with Team
LOCATION:Office
END:VEVENT
END:VCALENDAR
iCalendar es un formato utilizado para intercambiar datos de eventos de calendario, como reuniones, eventos y tareas. Su estructura se organiza en bloques como BEGIN:VEVENT para eventos individuales, con atributos como DTSTART y SUMMARY que definen los detalles del evento.
### vCard 
BEGIN:VCARD
VERSION:4.0
FN:John Doe
ORG:Example Corporation
TEL:+1234567890
EMAIL:john.doe@example.com
END:VCARD
vCard es un formato estándar para el intercambio de información de contacto, como nombres, direcciones, teléfonos y correos electrónicos. La estructura se basa en pares de clave-valor, por ejemplo, FN para el nombre completo y EMAIL para el correo electrónico.
### KML
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Eiffel Tower</name>
    <description>A famous landmark in Paris, France</description>
    <Point>
      <coordinates>2.2945,48.8584,0</coordinates>
    </Point>
  </Placemark>
</kml>
KML es un lenguaje de marcado basado en XML diseñado para representar datos geoespaciales, como ubicaciones y rutas en mapas. Se utilizan elementos como <Placemark> para definir puntos de interés, con etiquetas como <name> y <coordinates>.

### RSS
<?xml version="1.0"?>
<rss version="2.0">
  <channel>
    <title>Sample RSS Feed</title>
    <link>http://www.example.com/</link>
    <description>This is a sample RSS feed</description>
    <item>
      <title>First Article</title>
      <link>http://www.example.com/articles/1</link>
      <description>This is the first article description.</description>
      <pubDate>Tue, 01 Oct 2024 09:00:00 GMT</pubDate>
    </item>
  </channel>
</rss>
RSS es un formato basado en XML que permite la sindicación de contenido web, como noticias o artículos de blogs. Se estructura con un nodo <channel> que agrupa varias entradas o artículos (<item>), cada uno con un título, enlace y descripción.