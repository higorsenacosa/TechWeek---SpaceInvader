<html>
  <h1> <img src="https://github.com/higorsenacosa/TechWeek---SpaceInvader/assets/110289392/acf939ee-2ec1-4caf-98cb-8b7f447e4945" width="30px">  Sobre o evento</h1>
</html>
Os avanços da inteligência artificial e seus impactos em nossas vidas:" é o ponto de partida para a reflexão sobre o tema. O nosso evento convida profissionais que dialogam com Tecnologia, Game, Arquitetura e Design, para apresentarem suas trajetórias e seus projetos. O objetivo é proporcionar experiências e referências para todos os participantes, estimulando a criação de repertório.

# :information_source: Sobre a oficina
A oficina de desenvolvimento de jogos digitais utilizando Python e Pygame, durante a qual os participantes terão a oportunidade de criar um jogo inspirado no clássico Space Invaders, utilizando a plataforma Replit e a linguagem de programação Python.



# :computer: Vamos programar
Para executar o jogo, é imprescindível utilizar o Python como a linguagem de programação.
<html>
  <h2> <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/Python-Dark.svg" width='20px'> Instalar o Python</h2>
</html>

Para adquirir o Python, é necessário acessar o site oficial em [https://www.python.org/](https://www.python.org/) ou executar o comando correspondente no Shell:
<details>
  <summary><img src="https://raw.githubusercontent.com/gist/Xainey/d5bde7d01dcbac51ac951810e94313aa/raw/6c858c46726541b48ddaaebab29c41c07a196394/PowerShell.svg" width="16px"> PowerShell</summary>

  ```powershell
# Comando para Windows
winget install Python.Python.3.12
  ```
</details>
<details> 
  <summary><img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Bash_Logo_Colored.svg" width="16px"> Bash</summary>

  ```bash
# Comando para Distro's Linux
sudo apt install python3.12
  ```
</details>
<html>
  <h2> <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/VSCode-Dark.svg" width='20px'> Instalar o VSCode</h2>
</html>

Após a instalação do Python, podemos iniciar nossa jornada utilizando o Visual Studio Code. Para isso, é possível instalar o Visual Studio Code acessando o site oficial em [https://code.visualstudio.com/download](https://code.visualstudio.com/download) ou executando o comando correspondente no Shell:
<details>
  <summary> <img src="https://raw.githubusercontent.com/gist/Xainey/d5bde7d01dcbac51ac951810e94313aa/raw/6c858c46726541b48ddaaebab29c41c07a196394/PowerShell.svg" width="16px"> PowerShell</summary>
  

  ```powershell
# Comando para Windows
winget install vscode

  ```
</details>
<details>
  <summary><img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Bash_Logo_Colored.svg" width="16px"> Bash</summary>

  ```bash
# Comando para Distro's Linux
sudo apt install code
  ```
</details>

## :wrench: Preparando o ambiente do VSCode
<html>Ao abrir o Visual Studio Code, vamos pesquisar pelas extensões <img src="https://github.com/higorsenacosa/TechWeek---SpaceInvader/assets/110289392/dda0b7b1-ef89-4652-82a1-88e2cc769445" width='16px'>:</html>

 * <html><img src="https://github.com/higorsenacosa/TechWeek---SpaceInvader/assets/110289392/b6292f25-4f71-4b49-ad2f-3bb77d55ed81" width='16px'> <a href="https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode" target="_blank">IntelliCode</a></html>
 * <html><img src="https://github.com/tandpfun/skill-icons/blob/main/icons/Python-Dark.svg" width='16px'> <a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python" target="_blank">Python</a></html>
 * <html><img src="https://github.com/higorsenacosa/TechWeek---SpaceInvader/assets/110289392/d8444d8c-7adf-4c23-865b-c07aaae3bb9a" width='16px'> <a href="https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-pt-BR" target="_blank">Portuguese (Brazil) Language Pack for Visual Studio Code</a></html>
Quando finalizar a instalação das extensões, reinicie o VSCode e vamos para onde esté o código e abrir o VSCode por lá.

Quando chegar, vamos apertar a combinação de teclas `CTRL + '` e digitar o seguinte comando:
```bash
python -m venv .venv
```
Depois o comando:
```bash
.\.venv\Scripts\activate 
```
E por fim:
```bash
pip install pygame
```
