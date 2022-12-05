## DockerFile

Este é um repositório que criamos para armazenar o DockerFile com a imagem direcionada ao [Flowable](https://www.flowable.com/)

**Índice**

<!--ts-->

* [Sobre](#sobre)
* [Pré-requisitos](#ferramentas)
* [Como utilizar](#util)
* [Contribuintes](#contrib)
* [Docker Help - Referências](#help)
<!--te -->

<div id='sobre'>

### ⚙ Sobre Flowable

Com a missão de adiquirirmos conhecimento sobre a ferramenta [Flowable](https://www.flowable.com/) que é um mecanismo de fluxo
de trabalho de código aberto escrito em Java que pode executar processos de negócios descritos no [BPMN](https://www.lucidchart.com/pages/pt/o-que-e-bpmn)
(de forma simples é uma notação onde modelamos processos atraves de fluxos tornando esse processo mais agil e eficiente) recebemos a tarefa de construir uma imagem para rodarmos o 
flowable em outras maquinas apenas rodando o script/roteiro do docker onde optamos no momento por seguir com o conceito de [Docker Compose](https://docs.docker.com/compose/gettingstarted/). (flowable-ui e flowable-rest)

<div id='ferramentas'>

### 🦴 Pré requisitos

Saber o conceito de images e containers
<!--ts-->
* _Images_: Uma imagem é um modelo read-only com instruções para criar um contêiner Docker. Uma imagem é baseada em outra imagem, com alguma customização adicional.
* _Containers_: Um contêiner é uma instância executável de uma imagem. Você pode criar, iniciar, parar, mover ou excluir um contêiner usando a API ou CLI do Docker.
<!--te-->

#### 🧱 Utilizamos para construção desse Dockerfile:
<!--ts-->
* [Visual Studio Code](https://code.visualstudio.com/) (Editor de código-fonte)
* [Docker](https://www.docker.com/) (Testes do arquivo)
* [Docker Hub](https://hub.docker.com/search?q=flowable) (Este é um registro usado para hospedar e baixar diversas imagens)
<!--te-->

<div id='util'>

### 🛠️ Abrir e rodar o projeto
<!--ts-->
 
 * Antes de tudo verifique se o docker está inicializado (para verificar é simples, nos ícones ocultos fica símbolo de baleia com a seguinte frase: "🐋 Docker Desktop running")
 * Logo após isso clone esse repositório e passe a sua instancia local
 * Abra o cmd e rode o comendo "docker-compose up"
 
 * E pronto sua máquina está rodando o flowable, simples não?


<!-- 🛂(EM TESTES)
* Antes de tudo verifique se o docker está inicializado (para verificar é simples, nos icones ocultos fica simbolo de baleia com a seguinte frase: "🐋 Docker Desktop running")
* Logo após isso clone esse repositorio e passe a sua instancia local
* Dentro da pasta de transferencia abra o CMD e rode o seguinte comando "docker build -t flowable-ui -target flowable-rest"

* E pronto sua maquina esta rodando o flowable, simples não?  🛂(EM TESTES) -->

<!--te-->

<div id='contrib'>

### 👩‍💻 Contribuintes

A principal contribuinte com essa tarefa foi a [Deysi Lopes](https://github.com/DeysiLopes)

<div id='help'>

## 💻 Referências 

- https://docs.docker.com/get-started/overview/#docker-objects
- https://docs.docker.com/get-started/02_our_app/
- https://www.youtube.com/watch?v=pf7-3jHXEz0
- https://www.youtube.com/watch?v=5QGexrfqu60&t=12s
- https://www.macoratti.net/19/02/dock_imgfile1.htm
- https://pt.stackoverflow.com/questions/447482/qual-a-diferen%C3%A7a-entre-docker-compose-e-dockerfile
- https://blog.purestorage.com/purely-informational/docker-compose-vs-dockerfile-with-code-examples/
- https://takacsmark.com/dockerfile-tutorial-by-example-dockerfile-best-practices-2018/
- https://www.youtube.com/watch?v=SnSH8Ht3MIc
- https://www.youtube.com/watch?v=bhBSlnQcq2k
- https://blog.4linux.com.br/docker-compose-explicado/
