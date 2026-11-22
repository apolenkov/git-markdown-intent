# git-markdown-intent

Учебный проект к шагу «Markdown, Git, GitLab» курса «Анализ с ИИ-агентами»:
https://apolenkov.github.io/customdev-learning/guides/p2-git.html

## С чего начать

- `main` — исходная точка упражнения: `intent.md` с проблемой, границами и задачей. Предела выгрузки в нём ещё нет.
- Получите свою копию. В GitLab: **New project → Import project → Repository by URL** с адресом этого репозитория.
  На GitHub: **Fork**. В терминале: `git clone <адрес вашей копии>`.
- Дальше идите по шагам урока: ветка `limit-rows`, правка, Merge Request, замечание, исправление, слияние.

## С чем сверить результат

Ветка `example/limit-rows` — разобранный пример: два коммита ученика, как в уроке.

- В интерфейсе: **Compare** `main...example/limit-rows`.
- В терминале: `git diff main...example/limit-rows -- intent.md`.

Ожидаемый итог: в разделе «Границы» появился пункт «Если строк больше 10 000, система предлагает сузить фильтр».
