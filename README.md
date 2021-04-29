# Localizador_de_IP
Módulo Python para localizar IP consumindo múltiplas APIs de geolocalização. 

O script se resume a uma classe python "Finder" onde uma vez definindo o objeto IP e chamando o método "get_location" é possível obter a cidade, o país, a latitude e a longitude do IP requisitado através dos objetos **_self.city_** , **_self.country_** , **_self.latitude_** e **_self.longitude_** respectivamente. Esse trabalho é feito através da requisição de seis APIs de geolocalização, as quais, duas dessas requerem uma api key. Caso nenhum IP seja definido, a localização obtida será a localização local.

É possível tembém obter a confiabilidade da informação em porcentagem no formato string através dos objetos  **_self.latitude_reliability_** , **_self.latitude_reliability_** e **_self.longitude_reliability_**. Essa confiabilidade é calculada através da razão entre o número de APIs que retornaram a moda do conjunto em questão e o total de APIs requisistadas.

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

#1

<a href="https://imgbb.com/"><img src="https://i.ibb.co/M73g3dx/sda.png" alt="sda" border="0"></a>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/dtyvppb/foghdfoi.png" alt="foghdfoi" border="0"></a>

#2

<a href="https://imgbb.com/"><img src="https://i.ibb.co/bXPfPhY/xvdffgldmdfl.png" alt="xvdffgldmdfl" border="0"></a>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/VQdyv02/fwhehkjku.png" alt="fwhehkjku" border="0"></a>

#3

<a href="https://ibb.co/NTjt3RH"><img src="https://i.ibb.co/g4Tm7YB/ddfds.png" alt="ddfds" border="0"></a>

<a href="https://ibb.co/VCyxFrP"><img src="https://i.ibb.co/s1SCTkM/iadfuvoshdfsuhbfpdnhh.png" alt="iadfuvoshdfsuhbfpdnhh" border="0"></a>
