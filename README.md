# Localizador_de_IP
Módulo Python para localizar IP consumindo múltiplas APIs de geolocalização. 

O script se resume a uma classe python onde uma vez definindo o objeto IP e chamando o método "get_location" é possível obter a cidade, o país, a latitude e a longitude do IP requisitado através dos objetos **_self.city_** , **_self.country_** , **_self.latitude_** e **_self.longitude_** respectivamente. Esse trabalho é feito através da requisição de seis API's de geolocalização, as quais, duas dessas requerem uma api key. Caso nenhum IP seja definido, a localização obtida será a localização local.

Fontes:
* <a href="http://extreme-ip-lookup.com">Extreme ip lookup</a>
* <a href="http://www.geoplugin.net">geoPlugin</a>
* <a href="https://ip-api.com/">ip-api</a>
* <a href="https://ipapi.co/">ipapi</a>
* <a href="https://hgbrasil.com/status/geoip">HG_Brasil</a>
* <a href="https://ipstack.com/">ipstack</a>

Se nenhuma api key for definida através dos objetos **_self.HG_geoip_key_** e **_self.ipstack_key_**, o programa irá rodar, consultando apenas as quatro APIs abertas.

# Dependências 
* Requests 

_pip install requests_

* deep_translator

_pip install deep_translator_

# Exemplos de uso


