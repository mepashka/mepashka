### Hi there 👋
name: Repositories and diff history
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.lines.history.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_lines: yes
  plugin_lines_delay: 30
  plugin_lines_sections: repositories, history
  plugin_lines_repositories_limit: 2
  plugin_lines_history_limit: 1
  repositories_skipped: |
    @use.patterns
    */*
    +lowlighter/metrics

<!--
**mepashka/mepashka** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?mepashka=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
