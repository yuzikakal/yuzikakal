- 👋 Hi, I’m @yuzikakal
- 👀 I’m interested in programmig and artwork
- 🌱 I’m currently learning web programming, C++, and Java
- 📫 You can follow me at Instagram, Facebook, and X


![Repo History](https://github-readme-stats-eight-theta.vercel.app/api?username=yuzikakal&layout=compact&theme=tokyonight&hide_border=true) <br>
![My Favorite Language](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=yuzikakal&layout=compact&theme=tokyonight&hide_border=true)

![Views Count](https://komarev.com/ghpvc/?username=yuzikakal)
<!---
yuzikakal/yuzikakal is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.yuzikakal }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
