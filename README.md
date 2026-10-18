<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=220&section=header&text=Jo%C3%A3o%20Gime&fontSize=52&fontColor=58A6FF&desc=Programador%20web%20%7C%20PHP%20%26%20JavaScript&descSize=18&descAlignY=72&animation=fadeIn&color=0D1117&stroke=1F6FEB" alt="Banner de João Gime" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=500&lines=Programador+web;PHP+%2B+JavaScript" alt="Animação de texto: programador web, PHP e JavaScript" />

</div>

## Sobre mim

Sou João Gime, programador web. Trabalho com PHP e JavaScript. Este perfil reúne meus projetos e atividades no GitHub.

## Tecnologias

<div align="center">
  <img src="https://skillicons.dev/icons?i=php,js&theme=dark" alt="PHP e JavaScript" />
</div>

## GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=gimeao&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9&rank_icon=github" alt="Estatísticas do GitHub de João Gime" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gimeao&layout=compact&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Linguagens mais usadas por João Gime" />
</div>

## Streak

<div align="center">
  <img src="https://streak-stats.demolab.com?user=gimeao&theme=transparent&hide_border=true&ring=1F6FEB&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=8B949E&dates=8B949E" alt="Sequência de contribuições no GitHub" />
</div>

## Atividade

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=gimeao&bg_color=0D1117&color=58A6FF&line=1F6FEB&point=79C0FF&area=true&hide_border=true" alt="Gráfico de atividade do GitHub" width="100%" />
</div>

## GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=gimeao&theme=onestar&no-frame=true&no-bg=true&margin-w=8" alt="Troféus do GitHub" />
</div>

## Snake de contribuições

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gimeao/gimeao/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gimeao/gimeao/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/gimeao/gimeao/output/github-snake.svg" alt="Animação Snake do gráfico de contribuições" />
  </picture>
</div>

<!-- A imagem da Snake precisa dos SVGs publicados na branch output por uma GitHub Action. O README sozinho não executa a Action. <citation src="1,3"></citation> -->

<details>
  <summary>Configuração necessária para gerar a Snake</summary>

Crie o arquivo `.github/workflows/snake.yml` no repositório de perfil `gimeao/gimeao` com este conteúdo. Depois, execute o workflow pela aba **Actions**. Se a publicação falhar por permissões, habilite **Read and write permissions** nas configurações de Actions do repositório.

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: read

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest

    steps:
      - name: Generate snake SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: gimeao
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - name: Publish SVGs to the output branch
        uses: crazy-max/ghaction-github-pages@v5
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

<!-- A Action gera os arquivos definidos em outputs e os publica na branch indicada. <citation src="1,2,3"></citation> -->

</details>

## Redes sociais

<div align="center">
  <a href="https://www.linkedin.com/in/jo%C3%A3o-gime">
    <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=58A6FF" alt="LinkedIn" />
  </a>
  <a href="https://www.instagram.com/gime.ao/">
    <img src="https://img.shields.io/badge/Instagram-0D1117?style=for-the-badge&logo=instagram&logoColor=58A6FF" alt="Instagram" />
  </a>
</div>

<br />

<div align="center">
  <sub>Obrigado pela visita. Até a próxima linha de código.</sub>
</div>
````*
