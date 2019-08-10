# Projeto: Painel Solar + Detecção da Posição do Sol

# Descrição

  O projeto consiste em um painel solar móvel que, por meio de um microcontrolador Arduino Uno, detecta onde há maior incidência de luz solar e se move para tal ponto. Tal projeto pode ser usado, por exemplo, para alimentar baterias de pequeno porte do aeromodelismo, como baterias de liPo de drones. O projeto ainda conta com um display de 7 segmentos que mostra o nível tensão da placa solar.

## No futuro

  No futuro, espero aplicar à esse projeto uma integração de interface com internet, utilizando um raspberry Pi, que disponibilizaria um diagnóstico de como está funcionando a placa solar (dados como potência, correntes, tensão da placa e, se houver uma bateria sendo carregada, o nível de carga da mesma).
  É importante ressaltar também que essa versão com uma placa solar pequena é feita didaticamente e representa um sistema real de alimentação por placas solares de grande porte em uma casa ou um carro elétrico, por exemplo.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Pré-requisitos

  Primeiramente, faz-se necessário:
  - Arduino Uno e sua IDE
  
  - 4 Servo-Motores (2 x 9G)
  
  - 1 Shield Arduino Personalizado
  
  - 1 Shield personalizado para segurar os sensores (Sensor Holder PCB)
  
  - 4 Sensores LDR (PHOTOCELL 3K-11K OHM 5.10MM)
  
  - 4 Conjuntos de Cabo Jumper (Fêmea-Fêmea)
  
  - Display de 7 Segmentos com 3 Dígitos
  
  - Acesso a uma impressora 3D ou Cortadora à laser ou Fresadora Router CNC
  



```
Give examples
```

### Instalação

Em primeiro lugar, deve-se posicionar o Shield e o Sensor Holder, 

Após obter as peças de madeira individuais, deve-se seguir o passo a passo [deste vídeo do Youtube](https://www.youtube.com/watch?v=ehgPL8rRmDY) para que se construa a parte estrutural do projeto.

A partir daí, é hora de realizar a ligação elétrica, conforme diagrama feito no fritzing, do arduino com o resto do circuito, além de conectá-lo ao display de 7 segmentos.

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Realizando Testes

Existe apenas um teste que deve ser feito para ver se o sistema está funcionando.
Utilize uma lanterna para simular o sol sob os sensores LDR, faça um movimento horizontal ou vertical e observe se o painel solar se movimento seguindo a fonte de luz.

No geral, se algo não funciar, as seguintessituações podem ter ocorrido:

- Jumpers conectados errado, tenha certeza que os sensores estão indo na ordem certa para o shield. (Nesse caso o painel não lhe seguiria na direção certa)

- Servo-Motor estragado. (Nesse caso você ouvirá um barulho de metal vindo de dentro do motor)

- Arduino pode não estar ligado à um cabo de alimentação USB (Nesse caso o Arduino não fará nada)

- Código não teve seu upload para dentro do Arduino. (Nesse caso tambem o Arduino não fará nada)


### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

