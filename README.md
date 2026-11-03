# xuyiqing.github.io

The teaching index at <https://xuyiqing.github.io/>: links to Yiqing Xu's course sites. Each
course has its own repository and site (for example
[panel-lectures](https://github.com/xuyiqing/panel-lectures)).

**Since 2026-11-03 this user site has the custom domain `teaching.yiqingxu.org`** (file `docs/CNAME`; DNS: a CNAME
record `teaching` -> `xuyiqing.github.io` at Sitelio). Every project site without its own domain is served under it
(`teaching.yiqingxu.org/panel-lectures/` ...), and GitHub forwards the old `xuyiqing.github.io/...` addresses there.

**Since 2026-11-02 the front page redirects to <https://yiqingxu.org/teaching/>**, where the course list now
lives: `docs/index.html` is a hand-written redirect. Running `quarto render` in `site/` would overwrite it with the
old index, so don't, unless the redirect is meant to go.

The old page's Quarto source is in `site/`; `quarto render` there writes it to `docs/`, which GitHub
Pages serves. The 2021 Jekyll blog that used to live here is in the git history.
