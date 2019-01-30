# Hashme Ads

Hashme Ads es una plataforma de marketing de anuncios éticos y discretos que financia a los promotores culturales y otros contribuyentes sociales. 

Por medio de Hashme Ads los gestores culturales, creadores digitales y otros contribuyentes a las comunidades abiertas, pueden generar un ingreso lateral de manera sostenible, acompañados por un ecosistema open source.

## Tabla de contenidos

  - [Marketing Ético](#marketing-ético)
  - [¿Por qué?](#por-qué)
  - [¿Cómo?](cómo)
  - [¿Quién Anuncia en Hashme?](Quién Anuncia en Hashme)
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
* [More about how/why to interact with web3 here](https://gitcoin.co/web3).

Técnicamente, el sistema está diseñado así:

Web3 La principal fuente de confianza para el sistema es Ethereum blockchain. Echa un vistazo a los contratos inteligentes.
Web2 Esta parte de la app está construida con -----, y un puñado de otras herramientas que son comunes en el ecosistema web2.
Web 3 Bridge Este es el puente entre web3 y el resto de la aplicación. Mayormente está constrido sobre javascript(web3js) and python(web3py).
Brochureware Solo una bonita y pequeña página de destino que le dice a la gente qué es el proyecto.

## ¿Quién Anuncia en Hashme?

El Converter
El Anunciante
El Padrino

Ayudamos a que sus proyectos culturales favoritos prosperen pagando a los gestores la mayoría de todos los ingresos generados.

## Publisher JavaScript Embedding

### Optional Query String Parameters

### Embed Callbacks

## API

## Ad Rendering and Impression/Click Tracking

## Enums

## Code Standards

## Deployment

### Preboot

### Scheduler

### Database

## Maxmind

## Instrumentation

