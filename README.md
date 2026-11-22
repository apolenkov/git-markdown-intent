# git-markdown-intent

Учебный проект к шагу «Markdown, Git, GitLab» курса «Анализ с ИИ-агентами»:
https://apolenkov.github.io/customdev-learning/guides/p2-git.html

## С чего начать

- `main` — исходная точка упражнения: `intent.md` с проблемой, границами и задачей. Предела выгрузки в нём ещё нет.
- Получите свою копию. В GitLab: **New project → Import project → Repository by URL** с адресом этого репозитория.
  На GitHub: **Fork**. При Fork на GitHub снимите флажок **Copy the main branch only**, иначе ветки `example/limit-rows` в вашей копии не будет.
  В терминале: `git clone <адрес вашей копии>`.
- Дальше идите по шагам урока: ветка `limit-rows`, правка, Merge Request, замечание, исправление, слияние.
- Ответьте на замечание в том же запросе, получите Approve по исправленной версии, затем нажмите **Merge**. Второй запрос не создавайте.

## С чем сверить результат

Ветка `example/limit-rows` — разобранный пример: два коммита ученика, как в уроке.

- В интерфейсе: **Compare** `main...example/limit-rows`.
- В терминале: `git fetch origin`, затем `git diff origin/main...origin/example/limit-rows -- intent.md`.

Ожидаемый итог: в разделе «Границы» появился пункт «Если строк больше 10 000, система предлагает сузить фильтр».

## Шаблон запроса

Для GitLab скопируйте этот текст в описание MR из `.github/pull_request_template.md`.
