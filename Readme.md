# Introdução ao Docker

> Baseado em [https://docs.docker.com/get-started/overview/](https://docs.docker.com/get-started/overview/)

## Visão geral

Docker é uma plataforma aberta para desenvolvimento, implantação e execução de aplicativos. O Docker permite que você separe seus aplicativos de sua infraestrutura para que possa entregar o software rapidamente. Com o Docker, você pode gerenciar sua infraestrutura da mesma forma que gerencia seus aplicativos. Tirando proveito das metodologias do Docker para implantar, testar e implantar código rapidamente, você pode reduzir significativamente o atraso entre a escrita do código e sua execução na produção. (**Lead Time**).

## A plataforma Docker

O Docker oferece a capacidade de empacotar e executar um aplicativo em um ambiente isolado denominado contêiner. O isolamento e a segurança permitem que você execute vários contêineres simultaneamente em um determinado host. Os contêineres são leves porque não precisam da carga extra de um hipervisor, mas são executados diretamente no kernel da máquina host. Isso significa que você pode executar mais contêineres em uma determinada combinação de hardware do que se estivesse usando máquinas virtuais. Você pode até mesmo executar contêineres Docker em máquinas host que são na verdade máquinas virtuais!

O Docker fornece ferramentas e uma plataforma para gerenciar o ciclo de vida de seus contêineres:

- Desenvolva seu aplicativo e seus componentes de suporte usando contêineres;
- O contêiner se torna a unidade para distribuição e teste de seu aplicativo;
- Quando estiver pronto, implante seu aplicativo em seu ambiente de produção, como um contêiner ou um serviço orquestrado. Isso funciona da mesma forma, quer seu ambiente de produção seja um data center local, um provedor de nuvem ou um híbrido dos dois.

## Docker Engine

O **Docker Engine** é um aplicativo cliente-servidor com estes componentes principais:

- Um servidor que é um tipo de programa de longa duração denominado processo **daemon** (o comando `dockerd`).

- Uma API REST que especifica interfaces que os programas podem usar para falar com o daemon e instruí-lo sobre o que fazer;

- Um cliente de interface de linha de comando (CLI) (o comando **docker**);
