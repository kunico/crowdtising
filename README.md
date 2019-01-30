# Hashme Ads

Hashme Ads es una plataforma de marketing de anuncios éticos y discretos que financia a los promotores culturales y otros contribuyentes sociales. 

Por medio de Hashme Ads los gestores culturales, creadores digitales y otros contribuyentes a las comunidades abiertas, pueden generar un ingreso lateral de manera sostenible, acompañados por un ecosistema open source.

## Tabla de contenidos

  - [Marketing Ético](#marketing-ético)
  - [¿Por qué?](#por-qué)
  - [¿Cómo?](#cómo)
  - [¿Quién Anuncia en Hashme?](#quién-anuncia-en-hashme)
    - [El Convertidor](#el-convertidor)
    - [El Anunciante](#el-anunciante)
    - [El Gestor](#el-gestor)
  - [Publisher JavaScript Embedding](#publisher-javascript-embedding)
    - [Optional Query String Parameters](#optional-query-string-parameters)
  - [API](#api)
  - [Ad Rendering and Impression/Click Tracking](#ad-rendering-and-impressionclick-tracking)
  - [Enums](#enums)
  - [Development Environment](#development-environment)
    - [Database Seeds](#database-seeds)
  - [Code Standards](#code-standards)
  - [Deployment](#deployment)
    - [Preboot](#preboot)
    - [Scheduler](#scheduler)
    - [Database](#database)
  - [Maxmind](#maxmind)
  - [Candidates for Modules extraction](#candidates-for-modules-extraction)
  - [Contributors](#contributors)


# Marketing Ético

Hemos adoptado la metodologías de “Marketing Ético” de ReadTheDocs y CodeFoundAd. Lo que esto significa es que nuestros anuncios:

* No rastrean ni hacen un perfil de los visitantes (sin cookies).
* No vuelve a comercializar ni revender datos de usuarios (no tenemos ninguno).
* Son relevantes para la audiencia [de] en el sitio web.
* Son discretos.
* Son 100% de código abierto.
* Retribuyen a la comunidad a través de [Crowdtising | Anuncios Comunitarios](https://crowdtising.org).

## ¿Por qué?
_____

## ¿Cómo?

Funcionalmente, la app tiene  has varias características clave:

* Contratos inteligentes -- Donde los problenmas financeados son guardados e indexados.
* Brochureware -- Describes the project.
* Explorador de problemas financiados -- Un index Un índice de búsqueda de todo el trabajo disponible en el sistema.
* Envío del problema financiada / Flujo de aceptación: interfaz entre la aplicación y web3. 
* API - HTTPS API
* Bot - El HashmeBot
* [Más acerca de por qué/cómo interactuar con web3 aquí](https://gitcoin.co/web3).

Técnicamente, el sistema está diseñado así:

* Web3 La principal fuente de confianza para el sistema es Ethereum blockchain. Echa un vistazo a los contratos inteligentes.
* Web2 Esta parte de la app está construida con -----, y un puñado de otras herramientas que son comunes en el ecosistema web2.
* Web 3 Bridge Este es el puente entre web3 y el resto de la aplicación. Mayormente está constrido sobre javascript(web3js) and python(web3py).
* Brochureware Solo una bonita y pequeña página de destino que le dice a la gente qué es el proyecto.

## ¿Quién Anuncia en Hashme?

### El Convertidor

El Convertidor mide el éxito de sus campañas de anuncios basado en los números. Están muy interesados en ver la mayor cantidad de conversiones en su sitio web (registros, trials, newsletters, etc) por el menor costo posible. Este es el tipo de anunciante más común. Trabajan 

Este es el tipo de anunciante más común. Trabajan con presupuestos ajustados y quieren demostrar que pueden obtener un rendimiento positivo de su inversión en publicidad (ROAS). La mayoría de los convertidores son pequeñas y medianas empresas que desean crecer y destacarse entre sus competidores.

### El Anunciante

Mide el éxito de sus campañas de anuncios principalmente generando conocimiento de la marca. Su objetivo no es tanto obtener conversiones directas de sus ubicaciones publicitarias, sino más bien asegurarse de que las personas sepan quiénes son, qué proporcionan y qué piensan de ellos cuando llegue el momento de tomar una decisión de compra. Mayormente son grandes compañías con un presupuesta grande.

### El Gestor

No considera las conversiones o el conocimiento de la marca como el objetivo principal. Su objetivo principal es estar realmente en-linea con sustentar proyectos sociales. Su deseo es brindar financiamiento a los proyectos culturales de la comunidad con muy poca importancia puesta en conocimiento de la marca o las conversiones. En mi experiencia con este tipo de grupos, he encontrado que por lo general son artistas. Entienden los problemas al rededor de la sostenibilidad de la gestión cultural y quieren ayudar es su principal objetivo.

Ayudamos a que sus proyectos culturales favoritos prosperen pagando a los gestores la mayoría de todos los ingresos generados.

## Publisher JavaScript Embedding

### Optional Query String Parameters

### Embed Callbacks

## API

## Ad Rendering and Impression/Click Tracking

## Enums

## Development Environment

### Database Seeds

## Code Standards

## Deployment
### Preboot
### Scheduler
### Database

## Maxmind

## Candidates for Modules extraction

## Contributors
