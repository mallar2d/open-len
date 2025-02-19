# Open LEN (In Development)

![full_logo_open_len](https://github.com/user-attachments/assets/6f1274e1-9f8d-484c-acbf-379dd97be285)


**Open LEN** - це модульний Discord-бот із вбудованим штучним інтелектом, системою модерації та інтерактивними можливостями. Бот створений для покращення взаємодії в спільноті та автоматизації адміністративних завдань.

## Основні можливості
- 🔹 **Штучний інтелект** – відповідає на повідомлення, аналізує контекст і персоналізується під користувача.
- 🔹 **Модерація** – автоматичні обмеження за спамом, фільтрація нецензурної лексики та контроль згадувань.
- 🔹 **Ігри та інтерактив** – вікторини, квести та персоналізовані рекомендації.

## Встановлення
### Передумови
- Python 3.10+
- Токен Discord бота

### Запуск
```bash
pip install -r requirements.txt --upgrade
python main.py --prod
```

## Налаштування
Перед запуском відредагуйте файл `.env`:
```ini
DEBUG_MODE=false

# Discord Bot Token
DISCORD_TOKEN=TOKEN

# API Keys
MISTRAL_API_KEY=TOKEN
```

## Використання
Приклади команд:
```bash
!"Напиши вірш про технології"
!порушення @User "Флуд"
!налаштування
```

## Ліцензія
Проєкт розповсюджується за ліцензією MIT.

---

> ⚡ Open LEN розвивається! Будемо раді вашим ідеям та контриб’юції!
> Очікуйте реліз відкритого коду бота скоро.

