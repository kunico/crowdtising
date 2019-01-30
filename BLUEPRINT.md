FORMAT: 1A9

HOST: api.hashme-ads.org

CrowdTising: Hashme Ads

# Hashme Ads

# Anuncio HTML [/properties/{property_id}/funder.html/?{template}{theme}{keywords}]

Retorna un fragmento de HTML que puedes agregar a tu página.

↓ _Tu server code debería hacer algo similar a el siguiente ejemplo._

```
require "open-uri"
response = open("https://api.crowdtising.org/properties/1/funder.html")
@ad_html = response.read # place this HTML on your page somewhere
```

↓ _Tu client SPA code debería hacer algo similar a el siguiente ejemplo._

```
const axios = require('axios');

axios.get('https://api.hashme-ads.org/properties/1/funder.html')
  .then(function (response) {
    document.getElementById("Hashme Ads").innerHTML = response.data;
  });
```

## Fetch Ad HTML para Property [GET]

  + Parámetros
    + property_id (number, required) - El id de la propiedad (sitio).
    + template (enum[string], optional) - La plantilla de anuncio publicitario a usar.
      _sobre escribe la configuración de la propiedad_
      + `bottom-bar`
      + `centered`
      + `default`
      + `horizontal`
      + `image-centered`
      + `image-only`
      + `square`
      + `vertical`
    + theme (enum[string], opcional) - El tema del anuncio a aplicar.
      _sobre escribe la configuración de la propiedad_
      + `dark`
      + `light`
      + `unstyled` - exclude styles, only HTML
    + keywords (enum[string], opcional) - Lista delimitada por comas de palabras clave de la propiedad utilizadas para encontrar un anuncio coincidente.
      _sobre escribe la configuración de la propiedad_
      + `Arte`
      + `Música`
      + `Teatro`
      + `Jazz`
      + `Pintutra`
      + `...` #TODO: Relevar palabras clave (hay algunas definidas en el prospecto).

+ Response 200 (text/html)

        <div id="cf" style="max-width: 330px; margin: 0 auto;"> <span> <span class="cf-wrapper" style="border-radius: 4px; padding: 15px; display: block; overflow: hidden; font-size: 14px; line-height: 1.4; text-align: left; background-color: rgba(0, 0, 0, 0.05); font-family: Helvetica;"> <a class="cf-img-wrapper" target="_blank" rel="noopener" style="float: left; margin-right: 15px;" href="https://hashme-ads.org/impressions/7ee965a5-e5b8-469a-afc8-f6b431b04aa6/click?campaign_id=126"></a> <a class="cf-text" target="_blank" rel="noopener" style="color: #333; text-decoration: none;" href="https://hashme-ads.org/impressions/7ee965a5-e5b8-469a-afc8-f6b431b04aa6/click?campaign_id=126"> <strong>Tired of being tracked?</strong> <span>Crowdtising Ads is a non-tracking ad platform that funds open source</span> </a> <a href="https://Crowdtising Ads.org" class="cf-powered-by" target="_blank" rel="noopener" style="margin-top: 5px; font-size: 12px; display: block; color: #777; text-decoration: none;"> <em>ethical</em> ad by Hashme Ads <img src="https://hashme-ads.org/display/7ee965a5-e5b8-469a-afc8-f6b431b04aa6.gif?template=default&amp;theme=light"> </a> </span> </span> </div>

+ Response 404 (text/html)

        Hashme Ads no tiene un anunciante para ustéd esta vez.

# Anuncio JSON [/properties/{property_id}/funder.json/?{template}{theme}{keywords}]

## Fetch Ad JSON for Property [GET]

  + Parámetros
    + property_id (number, required) - El id de la propiedad (sitio).
    + template (enum[string], optional) - La plantilla de anuncio publicitario a usar.
      _sobre escribe la configuración de la propiedad_
      + `bottom-bar`
      + `centered`
      + `default`
      + `horizontal`
      + `image-centered`
      + `image-only`
      + `square`
      + `vertical`
    + theme (enum[string], opcional) - El tema del anuncio a aplicar.
      _sobre escribe la configuración de la propiedad_
      + `dark`
      + `light`
      + `unstyled` - exclude styles, only HTML
    + keywords (enum[string], opcional) - Lista delimitada por comas de palabras clave de la propiedad utilizadas para encontrar un anuncio coincidente.
      _sobre escribe la configuración de la propiedad_
      + `Arte`
      + `Música`
      + `Teatro`
      + `Jazz`
      + `Pintutra`
      + `...` #TODO: Relevar palabras clave (hay algunas definidas en el prospecto).


+ Response 200 (application/json)

        {
          "campaignUrl": "https://hashme-ads.org/impressions/4737f03b-3e78-4a8c-a5ba-ba8b4f41ed80/click?campaign_id=144",
          "impressionUrl": "https://hashme-ads.org/display/4737f03b-3e78-4a8c-a5ba-ba8b4f41ed80.gif?template=default&theme=light",
          "hashmeAdsUrl": "https://hashme-ads.org",
          "fallback": true,
          "headline": "Why Hashme Ads?",
          "body": "🍪 Because cookies should come from your grandma, not from ads",
          "images": [
            {
              "url": "https://d3a2el5l1ud3kv.cloudfront.net/5hswXFgp9Mkwacdqhw5sc4cy",
              "width": 200,
              "height": 200,
              "format": "small"
            },
            {
              "url": "https://d3a2el5l1ud3kv.cloudfront.net/fLt4UvyyuExewym5KBoA7Yjp",
              "width": 512,
              "height": 320,
              "format": "wide"
            },
            {
              "url": "https://d3a2el5l1ud3kv.cloudfront.net/828gHMndjM3zyzDsuN9FdE1j",
              "width": 260,
              "height": 200,
              "format": "large"
            }
          ],
          "html": "<div id=\"cf\" style=\"max-width: 330px; margin: 0 auto;\"> <span> <span class=\"cf-wrapper\" style=\"border-radius: 4px; padding: 15px; display: block; overflow: hidden; font-size: 14px; line-height: 1.4; text-align: left; background-color: rgba(0, 0, 0, 0.05); font-family: Helvetica;\"> <a class=\"cf-img-wrapper\" target=\"_blank\" rel=\"noopener\" style=\"float: left; margin-right: 15px;\" href=\"https://hashme-ads.org/impressions/4737f03b-3e78-4a8c-a5ba-ba8b4f41ed80/click?campaign_id=144\"> <img border=\"0\" height=\"100\" width=\"130\" class=\"cf-img\" src=\"https://d3a2el5l1ud3kv.cloudfront.net/828gHMndjM3zyzDsuN9FdE1j\" style=\"vertical-align: middle; max-width: 130px; border: none;\"> </a> <a class=\"cf-text\" target=\"_blank\" rel=\"noopener\" style=\"color: #333; text-decoration: none;\" href=\"https://hashme-ads.org/impressions/4737f03b-3e78-4a8c-a5ba-ba8b4f41ed80/click?campaign_id=144\"> <strong>Why Crowdtising Ads?</strong> <span>🍪 Because cookies should come from your grandma, not from ads</span> </a> <a href=\"https://Crowdtising Ads.org\" class=\"cf-powered-by\" target=\"_blank\" rel=\"noopener\" style=\"margin-top: 5px; font-size: 12px; display: block; color: #777; text-decoration: none;\"> <em>ethical</em> ad by Crowdtising Ads <img src=\"https://hashme-ads.org/display/4737f03b-3e78-4a8c-a5ba-ba8b4f41ed80.gif?template=default&amp;theme=light\"> </a> </span> </span> </div>"
        }

+ Response 404 (text/html)

        {
          "message": "Hashme Ads does not have a advertiser for you at this time."
        }
