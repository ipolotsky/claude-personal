# claude-config

Репозиторий для хранения глобальной конфигурации Claude Code.

## Структура

- `CLAUDE.md` — глобальные инструкции для Claude Code
- `skills/` — кастомные скилы

## Установка

Для активации конфигурации создать симлинки. Команды выполняются из корня репозитория:

```bash
ln -s "$(pwd)/CLAUDE.md" ~/.claude/CLAUDE.md
ln -s "$(pwd)/skills" ~/.claude/skills
```

Проверить, что симлинки созданы:

```bash
ls -la ~/.claude/CLAUDE.md ~/.claude/skills
```
