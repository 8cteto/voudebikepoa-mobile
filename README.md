#VouDeBikePoa - Mobile Version 

![Vou de Bike POA](https://raw.githubusercontent.com/8cteto/voudebikepoa/master/assets/images/logo2.png)

Vou de Bike POA é uma ferramenta de apoio para todas as pessoas que utilizam a bicicleta como meio de transporte e que praticam o ciclismo como um estilo de vida contribuindo para a redução dos problemas de mobilidade urbana e para o meio ambiente, além de ser um hábito que contribui para a saúde dos praticantes do ciclismo.

Nossa ideia é facilitar seu passeio, além de torná-lo mais seguro e divertido. Hoje nossa App atende a cidade de Porto Alegre e nossa ideia é atender também outras cidades do Brasil.

As principais funcionalidades que você encontrará aqui são:

* A localização de todas as estações do Bike Poa
*Criação de rotas, incluindo a estação Bike Poa mais da sua localização atual e do seu local de destino

Funcionalidades em planejamento/implementação:

* Criação de rotas para quem possui bicicleta e não necessita das informações do Bike POA
* Criação de rotas seguras, incluindo as ciclovias e trajetos com menor incidência de acidentes de trânsito
* Criação de rotas incluindo espaços culturais de acordo com suas preferências
* Visualização da quantidade de bicicletas nas estações Bike POA
* Informações sobre o estado de funcionamento das bicicletas do Bike POA

Vou de Bike POA é um projeto open source criado pela equipe 8cteto e utiliza dados de fontes abertas da Prefeitura Municipal de Porto Alegre distribuídos no portal datapoa. Nossa ideia nasceu durante o evento GUDay 2014 promovido pela Sucesu-RS.

Se você se interessar, estamos abertos a novos colaboradores e novas ideias. Contribua!

Mande seu feedback através de nossa [fanpage](https://www.facebook.com/VouDeBikePOA)!

##Datasets abertos utilizados
* http://datapoa.com.br/dataset/bikepoa
* http://datapoa.com.br/dataset/ciclovias-implantadas
* http://datapoa.com.br/dataset/espacos-culturais
* http://datapoa.com.br/dataset/acidentes-de-transito

## Pre-Requirements
* [Android SDK Plataform 19] (http://developer.android.com/sdk/installing/index.html)

## Running
* Install [Apache Cordova](http://cordova.apache.org/docs/en/3.5.0/guide_cli_index.md.html#The%20Command-Line%20Interface) `sudo npm install -g cordova`
* Make sure you have installed the latest [Android SDK](http://developer.android.com/sdk/installing/index.html)
* Set Variables: `export PATH=${PATH}:_PATH-ANDROID-SDK_/platform-tools:_PATH-ANDROID-SDK_/tools`
* Test your environment running:
* `cordova help`
* `android help`
* `adb help`
* Go to the app folder `cd voudebikepoa-mobile`
* Run `cordova build`
* Run `cordova emulate android` to load android emulator
* Enjoy ;-)

## Resources
[Color palette](http://www.colourlovers.com/palette/155071/Rei_Ayanami)
