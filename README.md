# A Maze
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: VR Software Development
- Project: A Maze
- Aluna: Hyun Ji Lee


-Descricao do Projeto
	- Ao inicio do jogo, o jogador e posicionado no inicio do labirinto no espaco
	- Para navegar pelo labirinto, visualize as direcoes com a rotacao da cabeca
	e clique em um cubo verde
	- Para coletar as moedas e chave clique no objeto quando o círculo no meio da tela
	piscar
	- Existem 5 moedas escondidas no labirinto
	- Existe 1 chave escondida no labirinto, sem ela voce nao podera finalizar o jogo
	- Clique na porta para abri-la quando tiver coletado a chave para acessar o tesouro
	- Clique na Placa You Win para finalizar o jogo e voltar ao inicio do jogo/labirinto

-Nome da cena principal : Main - Only Scene

-Versao do Unity: [Unity LTS Release 2017.4.4](https://unity3d.com/unity/qa/lts-releases?version=2017.4)

-Versão do GVR SDK for Unity : [GVR SDK for Unity v1.100.1](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.100.1)

-Plataforma(s) de implantação prevista(s): Android 4.4 API 19 ou +Recente com Google Cardboard

o FrameRate tava mto baixo, deixei os objetos estaticos, assei as luzes(baking),
mudei shader do skybox para mobile > skybox > imagem de espaço, os shaders dos outros obj para mobile > (...), 
alterei a música de fundo, 
excluí as luzes, deixando somente o Sol,
que agora é uma lua, alterei as partículas da fonte
testei e o frameRate parece melhor...tem alguma forma de visualizar o frame rate 
em numeros no editor do Unity?

### About the Starter Project

The included starter project represents a new Unity project where the following have been done:

- All assets needed to complete the project according to the project rubric have been imported.

- The imported models have been placed in the scene and organized in the scene hierarchy.

- Colliders have been added to the `Coin`, `Key`, `Left_Door`, `Right_Door`, and `The_Temple` game objects, and to the `Maze` game object's child game objects.



### Related Repositories

- [VR Software Development - Creating Scripts](https://github.com/udacity/VR-Software-Development_Creating-Scripts/releases)

- [VR Software Development - Controlling Objects Using Code](https://github.com/udacity/VR-Software-Development_Controlling-Objects-Using-Code/releases)

- [VR Software Development - VR Interaction](https://github.com/udacity/VR-Software-Development_VR-Interaction/releases)

- [VR Software Development - Programming Animations](https://github.com/udacity/VR-Software-Development_Programming-Animations/releases)

- [VR Software Development - Physics and Audio](https://github.com/udacity/VR-Software-Development_Physics-and-Audio/releases)

- [VR Software Development - Advanced VR Scripting](https://github.com/udacity/VR-Software-Development_Advanced-VR-Scripting/releases)

- VR Software Development - A Maze# udacity-vrrn_a-Maze
