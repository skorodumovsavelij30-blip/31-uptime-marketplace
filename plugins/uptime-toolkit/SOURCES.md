# Источники скиллов

Пакет собран 20 октября 2026 года из локальных файлов проекта
`C:\Users\YTS-Comp4\Desktop\obuchenie`.

| Скилл | Локальный источник | Происхождение |
| --- | --- | --- |
| `golang-code-style` | `.agents/skills/golang-code-style/` | `samber/cc-skills-golang`, версия скилла `1.3.0`, автор `samber` |
| `vercel-react-best-practices` | `.agents/skills/vercel-react-best-practices/` | `vercel-labs/agent-skills`, версия скилла `1.0.0`, автор `vercel` |
| `playwright-ui-check` | `codex-playwright-mcp/.agents/skills/playwright-ui-check/` | Локальный скилл проекта |

Сведения о двух внешних источниках сохранены в `skills-lock.json` из корня
проекта. Этот файл фиксирует происхождение исходных скиллов, а не контрольную
сумму всего плагина.

Скопированы все 79 исходных файлов, включая справочные материалы, 70 правил
React/Next.js, вспомогательные файлы и 24 примера оценки Go.

## Изменения копий

В `skills/vercel-react-best-practices/AGENTS.md` исправлены три относительные
ссылки: перед именами `async-defer-await.md`,
`async-cheap-condition-before-await.md` и `server-hoist-static-io.md`
добавлено `rules/`. Исходные файлы проекта не изменены.

README внутри Vercel-скилла описывает также сборку в исходном репозитории.
Упомянутые там `src/`, `metadata.json`, `test-cases.json` и команды `pnpm`
не нужны для использования подготовленного скилла и не входят в локальную
установленную копию.

## Лицензии

Заголовки `SKILL.md` двух внешних скиллов указывают лицензию MIT.
Их авторство и заголовки сохранены. В локальных источниках полные файлы
лицензий отсутствовали. Для локального `playwright-ui-check` лицензия
не указана. Пакет подготовлен для личного локального тестирования.
