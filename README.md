#VouDeBikePoa - Mobile Version 

Um aplicativo que permite traçar rota entre um ponto de partida e destino utilizando as bicicletas do BikePoa.

De onde eu estiver, poderei pedir para chegar a algum lugar utilizando as bicicletas do BikePoa.

O software irá me sugerir o ponto mais próximo de onde eu estiver para pegar uma Bike e o ponto mais próximo do destino para devolve-la, além da rota entre estes pontos.

Poderei também selecionar se gostaria de utilizar a rota mais rápida ou mais segura, utilizando assim as ciclovias e talvez dados de acidentes.
Temos ainda a possibilidade de sugerir pontos turísticos e culturais na rota do passeio.

Poderemos tentar facilitar também passeios de bike com sua própria bicicleta, permitindo utilizar os recursos de rota segura ou rápida entre pontos de partida e destino.

Dataset que utilizaremos (se implementadas todas as funcionalidades):
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
