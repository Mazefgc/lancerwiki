---
mapCalc1: NaN
tags:
  - place
  - planet
  - Ierita
  - nautilus
  - GMS
---

Planeta terrestre habitado, 90% do tamanho da Terra, orbitado pelas luas [[Lua Atmos|Atmos]] e [[Lua Hydra|Hydra]]. Descoberto e explorado pela primeira vez em 2150 pela [[Grande Civilização Humana]] durante a [[Segunda Grande Diáspora Espacial]] . 

## Informações Geográficas

- Gravidade: Similar a terra (0.95)
- Habitação: Localizada em regiões específicas
- Atmosfera: Similar a terra em composição e densidade
- Fauna e Biomas: Diversificados, similares à Terra, porém com uma abundância de desertos nas latitudes próximo ao equador.
- Atividade econômica: Majoritariamente exploração de minérios raros([[Igni]]).
- Nível de infraestrutura: Possui apenas 1 porto espacial mediano, capaz de reparos básicos e manufatura e lançamento de espaçonaves pequenas. Possui cidades parcialmente desenvolvidas, com alguma colônias remotas espalhadas em certas regiões. 

### Mapas do planeta



> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`


```leaflet  
id: MapIeritaWithGrid
image: [[Ierita_Grid.png]]
bounds: [[0,0], [1200, 1800]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 500px ### Size of the leaflet embed in px on your screen  
width: 100% ### Size of the leaflet embed in your note  
lat: 600 ### To center the map, make this half of the map height.  
long: 900 ### To center the map, make this half of the map width.  
minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 2 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
[![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfFsnkRy2qXBOFYq7UeqjlwZehG3Ai8_7WrFJvS4L-YwDqG_4O8VHqGY8X0GiXZiIihPKWSv83Qw1aeKUtqd-SBPpU6jaTgzbfh8sqrtJ5c2igUE3ynMPXiib07mmkvIZYzK3nF?key=LdxIKO6F_CxuuECBn3tPE9_t)]()
```leaflet  
id: MapIeritaWithGrid
image: [[Ierita_FullStack.png]]
bounds: [[0,0], [1200, 1800]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 500px ### Size of the leaflet embed in px on your screen  
width: 100% ### Size of the leaflet embed in your note  
lat: 600 ### To center the map, make this half of the map height.  
long: 900 ### To center the map, make this half of the map width.  
minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 2 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```

### Facções
- [[Garaftan Company|Garaftan Co.]] (Companhia de Tecnologia Avançada e Extração de matéria prima)
	- [[Garaftan Defense Force|GDF]] (Garaftan Defense Force).
		- [[Vultures]] (Divisão especial da GDF)
- [[GERD]] (GMS Eritan Research and Development)
- [[ELF]] (Eritan Liberation Force)
- [[Nebula Engineering Firm|NEF]] (Nebula Engineering Firm)

## História
Ierita é um planeta que inicialmente foi ocupado pelas suas primeiras colônias de habitação em torno de 4000u, formando uma população local com sua cultura e nomenclaturas. 
Em 4300u, houve a chegada da [[GERD]] no planeta, que montou as primeiras colônias de trabalhadores e começou a explorá-lo devido a rumores da presença de minérios exóticos importantes para desenvolvimento de tecnologias. Entre elas, o destaque era em [[Igni]], um minério raro encontrado em formações rochosas em regiões áridas do planeta, que se demonstrou um material crucial para o desenvolvimento da primeira geração de [[Sistema de Interfaceamento Nervoso| Sistemas de Interfaceamento Nervoso]] , tecnologia utilizada em praticamente todos os dispositivos de controle e interfaceamento humano avançados, que requerem rápida resposta. Porém, [[Igni]] se demonstrava muito instável para esta aplicação, portanto uma alternativa sintética, [[Signi]], foi desenvolvida e produzida em 4600u, que trazia muito mais estabilidade comparada ao material original, em troca de perda de desempenho.

Em 4900u, a GERD vendeu as terras em posse para a [[Garaftan Company]], dado que já conseguia produzir uma quantia de material sintético muito mais eficiente que explorar, mesmo sendo um processo caro. Ierita acabou nunca se tornando um Core World, e longe da observação da União, Garaftan se tornou cada vez mais abusiva com sua exploração dos minérios e população local. 
O aumento das pressões sociopolíticas e militares entre a população Eritana e a corporação eventualmente resulta numa guerra civil em 4945u, onde várias terras Eritanas ao longo de um conflito que escalou e diminuiu ao longo de 40 anos foram tomadas, e o governo é capturado e controlado pela [[Garaftan Company|Garaftan Co.]] 
Uma região que tinha saúde, tecnologia, agricultura acessível e próspera numa sociedade comum, agora enfrenta um período de ditadura e pressão militar, com o acesso a muitas necessidades das mesmas infraestruturas barrados por incontáveis burocracias e regras, feitas para intimidar a população Eritana, e beneficiar os membros e partidários da Garaftan, numa espécie de sociedade fechada. Prisioneiros da guerra civil nunca mais foram vistos, e as cidades recebem cada vez menos suporte dos polos tecnológicos e agricultores que estão no controle da companhia.

O ano atual é 5000u, 15 anos após o fim da guerra civil, onde cidades estão cada vez mais pobres, porém a entrada da NEF ([[Nebula Engineering Firm]]) permitiu que as cidades longe dos pontos de interesse da Garaftan possam ter alguma infraestrutura tecnológica e robótica para auxiliar nas atividades econômicas de engenharia e agricultura, ainda sim longe de como eram no passado e muita mais em comparação da tecnologia da Garaftan. 
Cidades longe dos pontos de interesse são menos monitoradas e policiadas, porém o contato entre regiões é escasso e intencionalmente censurado e barrado pela Garaftan, isolando as populações ainda mais. Protestos, rebeliões violentas ainda existem, mas em geral as circunstâncias são as mesmas, e a maioria das pessoas presentes são presas, violentadas, ou simplesmente somem sem nenhum rastro.
Comércio de armamentos é estritamente proibido, e sistemas de saúde são tão inefetivos que é mais fácil conseguir uma prótese por contrabando do que pelos sistemas de saúde Eritanos. Impressoras 3d em sua maioria são da [[Nebula Engineering Firm|NEF]], e os produtos produzidos também são regulados. Travessia entre regiões populadas ainda é possível, mas os caminhos estabelecidos são repletos de pedágios e checkpoints da [[Garaftan Defense Force|GDF]]. Maior parte do policiamento é feito por drones autônomos nas cidades, sendo que apenas as cidades mais vigiadas tem uma quantia maior de agentes da [[Garaftan Defense Force|GDF]] presentes.

A capital [[Cuna Sovalye|Sovalye]] (de nome antigo/completo "Cuna Sovalye") da região de [[Agirroni]] é onde a campanha se inicia.


## Cultura

Seu nome dado pela cultura local é Keça Stêran (Filha das Estrelas), devido à sua formação.