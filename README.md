# Digital-preservartion-BR
[Preservação digital](https://en.wikipedia.org/wiki/Digital_preservation) das principais fontes  do **banco de dados AddressForAll-Brasil**, mantido pelo [Instituto AddressForAll](http://addressforall.org/).

## Fontes primárias 
As [fontes de dados primárias](https://en.wikipedia.org/wiki/Primary_source) podem ter diversas origens e diferentes metodologias de coleta. De especial interesse para o Instituto AddressForAll, no sentido de preservação de longo prazo (décadas)  são as fontes de endereços de cada município do Brasil. Cada fonte consiste de um conjunto de dados sistematizados e publicados **por uma instituição** (nacional ou internacional) com idoniedade reconhecida pela comunidade local.

As fontes primárias estão relacionadas aos [dados brutos](https://en.wikipedia.org/wiki/Raw_data), quando tidos como ["verdade de campo" ou  "verdade oficial"](https://wiki.openstreetmap.org/wiki/Ground_truth_and_Official_truth), e com o trabalho mobilizado pela instituição para sistematizar, consolidar ou transformar os dados brutos em dados geográficos consistentes. Dois exemplos ilustrativos:

* Um carteiro com seu [GPS](https://en.wikipedia.org/wiki/Global_Positioning_System), confirmando que o endereço de entrega existe e está localizado nas coordenadas de latitude e longitude indicadas pelo GPS. Diversos carteiros, entregadores e outros profissionais podem alimentar uma planilha e essa planilha por fim, publicada como [arquivo CSV](https://en.wikipedia.org/wiki/Comma-separated_values), será a nossa fonte primária de dados.

* [Imagens de satélite](https://en.wikipedia.org/wiki/Remote_sensing) são dados brutos. Os lotes, rios e vias são desenhados sobre a imagem a partir de softwares confiáveis assistidos por pessoas habilidadas, e que terão seu trabalho publicado (nan forma por exemplo de [arquivos GeoJSON](https://en.wikipedia.org/wiki/GeoJSON)) por instituições que "assinam embaixo" desse trabalho, tais como o IBGE, a Fundação OpenStreetMap, o departamento de cartografia de uma grande prefeitura, e muitos outros. <br/>Mesmo tendo  usado a mesma imagem como origem, os produtos podem diferir bastante em nível de qualidade, metodologia de interpretação e modelagem dos dados, de modo que cada produto é considerado uma fonte distinta.

### Fontes OpenStreetMap Geofabrik
O [mapa OSM](https://www.openstreetmap.org/about) cobre todo o planeta, é mantido pela [Openstreetmap Foundation](https://blog.osmfoundation.org/about/), uma fundação inglesa registrada sob *Company Registration Number 05912761*.

Diversos recortes do mapa OSM são gerados pela  [empresa alemã e membro da OSMF, Geofabrik](https://www.geofabrik.de/geofabrik/openstreetmap.html). Seus recortes são considerados fiáveis e utilizados por governos e empresas por todo o mundo, portanto  amplamente auditados. Por orientação do projeto  [OSM-Stable Brasil](https://github.com/OSMBrasil/stable) ([docs](http://addressforall.org/osms/)),  o Instituto AddressForAll também  faz uso desses recortes. 

Os metadados dos arquivos preservados estão descritos no *git* do projeto, [git/OSMBrasil/stable/brazil-latest.osm.md](https://github.com/OSMBrasil/stable/blob/master/brazil-latest.osm.md#dump-opensstreetmap-do-brasil).

## Fontes IBGE
Fonte dos dados estatísticos oficiais do Brasil, bem elementos de cartografia e localização de endereços. Por ser uma fonte muito extensa, requer  [curadoria e decisões de projeto](https://github.com/AddressForAll/digital-preservartion-BR/issues/1).


## Fontes nas prefeituras
Por ser uma fonte muito extensa e diversificada, requer  [curadoria e decisões de projeto](https://github.com/AddressForAll/digital-preservartion-BR/issues/1).




