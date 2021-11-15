# Bases de dados hidrológicos

Essa lista reúne algumas bases de dados abertos que podem ser úteis para estudos hidrológicos e climáticos.
A lista está em construção, caso você queira contribuir/adicionar alguma informação, é só entrar em contato ou enviar uma pull request.

## Dados hidrometeorológicos - Brasil

| Fonte | Dados disponíveis | Formato | Resolução temporal | Informações adicionais |
|  ---  |        ---        |   ---   |         ---        |          ---           |
| [Hidroweb](http://www.snirh.gov.br/hidroweb/) | Séries históricas de precipitação e vazão, hidrografia | csv | Diária | Tem API. Estações convencionais. |
| [INMET](https://portal.inmet.gov.br/dadoshistoricos) | Temperatura, Umidade relativa, Pto. Orvalho, Pressão, Vento, Radiação solar, Chuva | csv | Diária | Estações automáticas |
| [Sistema de acompanhamento de reservatórios - ANA](https://www.ana.gov.br/sar/) | Capacidade, volume armazenado, cota | csv | Diária | | 
| [CAMELS dataset](https://zenodo.org/record/3964745#.X0kNr8hKg2w) | Precipitação, vazão, evapotranspiração real, evapotranspiração potencial e temperatura mínima, média e máxima | csv | Diária | |
| [Funceme - Plataforma de coleta de dados](http://funceme.br/pcd) | Dados de estações agrometeorológicas, hidrológicas, meteorológicas e pluviométricas | csv | Variável | Tem API. Reune dados de diversas instituições |
| [Funceme - Monitoramento dos reservatórios do CE](http://funceme.br/pcd) | Cota, volume, CAV | csv | Diária, mensal | [Acesse a versão original do portal](http://www.hidro.ce.gov.br/) | 
| [SNIRH - Rede hidrometeorológica nacional](http://portal1.snirh.gov.br/ana/apps/webappviewer/index.html?id=e1abba60063d4c13a5594c5c8b4cba51) | Estações hidrometeorológicas, hidrografia | Shapefile | - | - |
| [Artigo - Int. Journal of Climatology](https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/joc.4518) | precipitação, temperatura máxima diária, temperatura mínima diária, radiação solar, velocidade do vento a 2 m e umidade relativa | NetCDF | Diária | Base de dados disponível [aqui](https://utexas.app.box.com/v/Xavier-etal-IJOC-DATA).
| [DAEE - SP](http://www.hidrologia.daee.sp.gov.br/) | Dados fluviométricos e pluviométricos do estado de SP | csv | Diária, mensal | - |
 
## Dados hidrometeorológicos - Global 
 
| Fonte | Dados disponíveis | Período | Formato | Resolução temporal | Informações adicionais |
|  ---  |        ---        |   ---   |   ---   |        ---         |          ---           |
| [NEO - NASA](https://neo.sci.gsfc.nasa.gov/) | Vapor d'água, radiação solar, albedo, TSM, precipitação | Depende da variável | JPEG, PNG, GeoTIFF, csv | Diária, mensal | Dados de satélite |
| [USGS](https://earthexplorer.usgs.gov/) | - | - | Shapefile, kmz | - | Dados de satélite |
| [ERA5](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5) | [Documentação](https://confluence.ecmwf.int/display/CKB/ERA5%3A+data+documentation) | 1979-2020 | NetCDF | Horária, diária, mensal | Dados de satélite |
| [Índices climáticos NOAA](https://www.ncdc.noaa.gov/cdo-web/datasets) | Índices meteorológicos, Normais climatológicas |  |  |  |  |  |

## Dados fisiográficos - Brasil

| Fonte | Dados disponíveis | Formato | Resolução espacial | Informações adicionais |
|  ---  |        ---        |   ---   |        ---         |          ---           |
| [ANA](http://dadosabertos.ana.gov.br/) | Delimitação de bacias, regiões hidrográficas, CN | Shapefile | - | Dados de satélite |
| [CNPM - EMBRAPA](https://www.cnpm.embrapa.br/projetos/relevobr/download/index.htm) | Modelos Numéricos de Elevação | Geotiff | 90 metros |  |
| [Topodata](http://www.webmapit.com.br/inpe/topodata/) | Modelo Digital de Elevação | Geotiff | 30 metros | [Elaborados a partir dos dados SRTM](http://www.dsr.inpe.br/topodata/index.php) |
| [Embrapa - Bases de dados de solos](https://www.embrapa.br/solos/sibcs/bases-de-dados-de-solos) | Perfis de solo, características morfológicas, físicas, químicas e mineralógicas | JPEG, PNG, GeoTIFF, csv | - | Dados obtidos a partir de projetos técnico-científicos da Embrapa |
| [CPRM - Hybras](http://www.cprm.gov.br/publique/Hidrologia/Pesquisa-e-Inovacao/HYBRAS-4930.html/) | Dados hidrofísicos de solo (condutividade hidráulica, retenção de água) | MS Access | Variável | [Manual e descrição dos dados](http://www.cprm.gov.br/publique/Hidrologia/Pesquisa-e-Inovacao/HYBRAS-4930.html)

### Outros dados

- [SIAGAS - Base de dados de poços](http://siagasweb.cprm.gov.br/layout/)
- [A review of freely accessible global datasets for the study of floods, droughts and their interactions with human societies](https://onlinelibrary.wiley.com/doi/full/10.1002/wat2.1424)
