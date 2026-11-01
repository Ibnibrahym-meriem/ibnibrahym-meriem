name: Générer l'animation des contributions

on:
  schedule:
    - cron: "0 0 * * *"   # chaque jour à minuit
  workflow_dispatch:       # lancement manuel
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 5
    steps:
      - name: Générer les SVG
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg?color_snake=#7C3AED&color_dots=#ebedf0,#ddd6fe,#c4b5fd,#a78bfa,#7c3aed
            dist/github-snake-dark.svg?palette=github-dark&color_snake=#A855F7&color_dots=#161b22,#2e1065,#5b21b6,#7c3aed,#a855f7

      - name: Publier sur la branche output
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
