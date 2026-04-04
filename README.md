# Python Installers Mirror

Зеркало официальных установщиков Python для Windows (x64).

## Доступные версии

- Python 3.13.12
- Python 3.12.10
- Python 3.11.9
- Python 3.10.11
- Python 3.9.13
- Python 3.8.10
- Python 3.7.9
- Python 3.6.8
- Python 3.5.4

## Установка

Скачайте нужную версию из [Releases](../../releases) и запустите установщик.

## Что это?

Это **официальные установщики Python**, скачанные с [python.org](https://www.python.org/) и размещенные здесь для удобства и быстрой загрузки.

**Никаких модификаций не вносилось** - все установщики идентичны оригинальным с python.org.

## Зачем это нужно?

1. **Быстрая загрузка** - GitHub CDN обычно работает быстрее, чем python.org
2. **Доступность** - python.org иногда недоступен или медленный в некоторых регионах
3. **Удобство** - все версии в одном месте

## Безопасность

Все файлы загружены с официального сайта python.org. Вы можете проверить контрольные суммы:

```bash
# Сравните с официальными MD5/SHA256 на python.org
certutil -hashfile python-3.12.8-amd64.exe SHA256
```

Официальные хэши: https://www.python.org/downloads/

## Лицензия

Python распространяется под **PSF License** (Python Software Foundation License).

Это permissive лицензия, разрешающая свободное использование, модификацию и распространение.

Полный текст лицензии: https://docs.python.org/3/license.html

## Отказ от ответственности

Этот репозиторий является **неофициальным зеркалом**. Мы не аффилированы с Python Software Foundation.

Все права на Python принадлежат Python Software Foundation и авторам.

Используйте на свой риск. Для производственных систем рекомендуется скачивать с официального сайта [python.org](https://www.python.org/).

## Как обновить версии

1. Скачайте новый установщик с [python.org](https://www.python.org/downloads/windows/)
2. Создайте новый Release на GitHub
3. Загрузите установщик в Release

Или используйте GitHub Actions (см. `.github/workflows/mirror.yml`)

## Ссылки

- Официальный сайт Python: https://www.python.org/
- Загрузки Python: https://www.python.org/downloads/
- Документация: https://docs.python.org/
- PSF License: https://docs.python.org/3/license.html

## Контакты

Если нашли проблему или хотите добавить версию - создайте Issue.
