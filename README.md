# Hey! Eu sou fefipe15-lgmt
Estudando lógica da programação
Estudando funções aplicadas no Github 🙀
Informática e Desenvolvimento de Sistemas
Projeto Multidisciplinar

<h1 align="center">⚡ ROOM MODE ⚡</h1>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&width=600&lines=Access+Granted...;Welcome+to+my+GitHub;Developer+%7C+Cybersecurity+%7C+Open+Source" />
</p>

 🧠 Sobre mim

bash
> Nome: Felipe - 
> Área: Desenvolvimento / Segurança
> Linguagens: Python, JavaScript, HTML
> Sistema: Linux
<p align="center"> <img src="https://skillicons.dev/icons?i=python,javascript,linux,git,github,vscode,html,css" /> </p>
<p align="center"> <img height="180em" src="https://github-readme-stats.vercel.app/api?username=SEU_USUARIO&show_icons=true&theme=chartreuse-dark"/> <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USUARIO&layout=compact&theme=chartreuse-dark"/> </p>
```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */24 * * *"

  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: SEU_USUARIO
          outputs: |
            dist/github-contribution-grid-snake.svg
