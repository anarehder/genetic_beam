
# Algoritmo Genético para corrosão anisotrópica de silício

## Você precisa ter instalado no seu computador:


## Vienna 
Acesse os repositorios para saber como instalar
### [viennaLS](https://github.com/ViennaTools/ViennaLS.git)
### [viennaAlignedWetEtch](https://github.com/XaverKlemenschits/ViennaLSAlignedWetEtch.git)


## OpenScad

```bash
    sudo add-apt-repository ppa:openscad/releases
    sudo apt update
    sudo apt install openscad
```


## Python
```bash
    sudo apt update
    sudo apt install python3
```


## Como usar este repositório?
Clone o repositorio e rode na pasta build o comando abaixo:

```bash
    git clone https://github.com/anarehder/genetic_beam.git
    cd genetic_beam
    cd build
    cmake .. -DCMAKE_INSTALL_PREFIX=/path/to/your/custom/install/
    make
    ./Algoritimo_Genetico_8
```
