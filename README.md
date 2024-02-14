### Hi there , Eu sou a Helen e seja Bem-Vindo ao meu Github👋

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=HelenCorecha&show_icons=true&theme=radical)


    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: HelenCorecha
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  
