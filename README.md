# ophix-lang-ru-server-base

> Русский языковой пакет для ophix-server-base.

Russian translation pack for [ophix-server-base](https://ophix.io).

## Install

```bash
pip install ophix-lang-ru-server-base
```

Then set `LANGUAGE_CODE = "ru"` in your server `.env`.

## What is translated

- Admin UI strings: client fieldset labels, deployment and token field labels
- Help text strings for Client model fields (deployment_ref, venv_name, venv_path, artifact permission flags)
- Documentation pages: server installation, client quickstart, access auditing

## Documentation

- [Установка сервера](src/ophix_lang_ru_server_base/docs/server-installation.md)
- [Быстрый старт клиента](src/ophix_lang_ru_server_base/docs/client-quickstart.md)
- [Журнал аудита доступа](src/ophix_lang_ru_server_base/docs/access-auditing.md)
