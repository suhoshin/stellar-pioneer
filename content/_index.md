---
# 내가 지정한 섹션만 렌더
_build:
  list: always
  render: always

sections:
  # 1) 짧은 Bio (hero)
  - block: hero
    content:
      title: "Suho Shin"
      text: |
        I'm a Ph.D. candidate in Computer Science at the University of Maryland, advised by [Prof. MohammadTaghi Hajiaghayi](http://www.cs.umd.edu/~hajiagha/).
        I study algorithmic game theory, especially delegated choice, mechanism design, and market design. I also work on online algorithms, approximation, and bandits for the modern digital economy.

        I'm on the **academic job market** this year (postdoc or faculty). Please feel free to reach out!
    design:
      align: left

  # 2) Selected Publications (줄글, 폭 넓힘)
  - block: markdown
    content:
      title: "Selected Publications"
      text: |
        <style>
          /* 이 섹션 안에서만 폭을 넓힌다 */
          .pubs-wide { max-width: 1100px; margin-left:auto; margin-right:auto; }
          .pubs-wide p, .pubs-wide li { max-width: none; }
        </style>

        <div class="pubs-wide">
        <em>(α, β denote alphabetical order of authorship)</em>

        * **Algorithmic Delegated Choice: Reading List**, [SIGecom Exchanges Vol 23.1](https://www.sigecom.org/exchanges/volume_23/1/HAJIAGHAYI.pdf)  
          * M. Hajiaghayi, S. Shin

        * **Optimal Contest for Recommender Systems**, [working paper](htt)*
