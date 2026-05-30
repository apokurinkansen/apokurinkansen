### Kubutaku

Data Engineer. データ基盤を整え、分析しやすい形に直す仕事をしています。
dbt と SQL でディメンショナルモデリングを書き、Python で隙間を埋める日々。
最近はソフトウェア設計をちゃんと勉強しなおしています。

---

#### Now

- 業務で dbt / BigQuery / Snowflake を使ったデータ基盤の構築・改善
- 副業的に TypeScript と React、ソフトウェア設計の学び直し
- 興味: ディメンショナルモデリング、データ契約、メタデータ駆動の自動化

#### Stack

`dbt` &nbsp; `SQL` &nbsp; `Python` &nbsp; `BigQuery` &nbsp; `Snowflake` &nbsp; `AWS` &nbsp; `GCP` &nbsp; `Git`

---

#### How I think about data

```
            ┌────────────┐
            │  fct_order │ ── grain: 1 row per order line
            └─────┬──────┘
       ┌──────────┼──────────┬───────────┐
   dim_customer  dim_date  dim_product  dim_store
        │           │          │            │
        └── slowly changing, surrogate-keyed, tested ──┘
```

小さく、明示的に、テストできる形で。

---

<!-- Contribution snake — generated daily by GitHub Actions (Platane/snk) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/apokurinkansen/apokurinkansen/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/apokurinkansen/apokurinkansen/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/apokurinkansen/apokurinkansen/output/github-contribution-grid-snake.svg"/>
</picture>

---

<a href="https://github.com/apokurinkansen">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=apokurinkansen&show_icons=true&count_private=true&hide_border=true&hide_title=true&bg_color=00000000&text_color=c9d1d9&icon_color=58a6ff&ring_color=58a6ff" alt="stats"/>
</a>
<a href="https://github.com/apokurinkansen">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=apokurinkansen&layout=compact&hide_border=true&bg_color=00000000&text_color=c9d1d9&title_color=58a6ff&langs_count=6" alt="top langs"/>
</a>

<br/><br/>

<sub>Thanks for stopping by.</sub>
