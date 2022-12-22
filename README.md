
## Welcome on board 👩‍🔬
--------
**Physicist** who moved into the world of **Data Science**.

🔬 Science is on my DNA.

🎨 ART is on my name.

🚴‍♀️ 🏃‍♀️ Cycling and montain running is my fuel.

📊 I like visualisations and to explain compicated topics in simple terms.

🖌 I love combine art and science.

📚 I love learning and discovering new things.

<!-- 🗺️ I can do without traveling and discovering new places and cultures.-->

<!--
> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.
> 🚵
> 👩‍🔬
> 🌍
> 📚 I love reading
<p> -->
🕸 <a href="https://odartsi.github.io/olympia_dartsi/"> Website</a> 

- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
       outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

<!--  
</p>
#### Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

<img src="[image.png](https://user-images.githubusercontent.com/58295268/180822737-d1b32dfd-56ed-45d4-acaf-010644f2773e.png)" width="200" height="100">

<!-- ![image](https://user-images.githubusercontent.com/58295268/180822737-d1b32dfd-56ed-45d4-acaf-010644f2773e.png) -->
