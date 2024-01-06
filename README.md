# Переклад bsky.app українською

Ласкаво просимо! Долучитись до роботи над перекладом можна на [Crowdin](https://crowdin.com/project/bsky-app-ua)

## Оновлення перекладу

Для того щоб переклад оновився, потрібно надіслати pull request до bluesky-social/social-app.

Для цього є автоматичний GitHub workflow який створює гілку у підходящому форматі.

1. Відкрити вкладку [Actions](https://github.com/imax9000/bsky-app-ua/actions/workflows/export.yml)
2. Натиснути "Run workflow" -> "Run workflow"
3. Дочекатись завершення
4. Перейти до гілки [`export`](https://github.com/imax9000/bsky-app-ua/tree/export)
5. Натиснути "Contribute" -> "Open pull request"
6. Проглянути зміни на предмет чогось неочікуваного
7. Якщо все гаразд - натиснути "Create pull request"

Якщо під час розгляду pull request'у виявляється що потрібно внести якісь зміни - можна запустити workflow ще раз. Це повністю заново згенерує гілку `export` з усіма змінами які були зроблені в Crowdin.
