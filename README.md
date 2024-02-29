# changelog-platform
Список оновлень платформи Smart Sender (не включає виправлень та оновлень продуктивності)


### 01.03.2024
- BETA: ["Зарезервовані змінні"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1716355073) тепер можна використовувати в умовах правил
- Біллінг: Поповнення балансу/оплата рахунку частіше 1 разу за 2 хвилини блокується для уникнення випадкових повторних оплат

### 27.02.2024
- Оновлено інструмент росту ["Instagram історії"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1685391629/Instagram). Додано функцію "Надіслати love реакцію у відповідь", додано фільтр за ключовими словами реакції. Очікується верифікація від Meta для додавання функції вибору окремої історії

### 21.02.2024
- BETA: Додано ["Зарезервовані змінні"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1716355073) (додаткові змінні, що заповнюються автоматично за певних умов)

### 13.02.2024
- Додано інструмент росту ["Привітання"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1797718017) для Telegram (аналог /setdescription в BotFather)
- Додано функцію [API "Створення контакту"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1686503454/Channels+API+-+ua) (лише WhatsApp)
- Додано можливість запускати Прев'ю воронки з будь-якого блоку
- Додано можливість пропускати затримки/розклад в прев'ю воронки (замість затримки надсилатиметься інформаційне повідомлення про відповідну затримку)

### 12.02.2024
- Додано (активовано) інструмент росту ["Opt-In"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1684965013/Opt-in) для WhatsApp

### 10.02.2024
- Додано інструмент росту ["Шаблони WhatsApp"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1861550228/WhatsApp). Повідомлення, які можна відправляти поза 24-годинним вікном
  
  Для відправки шаблону через "Живі чати" користуйтеся інструментом росту "[Швидкі відповіді](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1684866573)"

### 27.01.2024
- Додано [канал WhatsApp](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1846673662/WhatsApp+-+ua) (пряма інтеграція з Meta без посередників)

  Також працює [імпорт](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1685618693) контактів у цей канал. В якості ідентифікаторів необхідно вказувати номер телефону

### 14.11.2023
- Додано інструмент росту ["Привітання"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1797718017) для Facebook

### 11.11.2023
- Додано інструмент росту ["Стартові списки"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1797357626) для Facebook
- Додано інструмент росту ["Статичне меню"](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1684866819) для instagram
- Переміщені окремі елементи у правильні інструменти росту (Тобто нічого не пропало, а "переїхало" у правильний інструмент росту)

### 10.11.2023
- Додано відображення папок змінних в картці контакту в "Живих чатах"

### 02.11.2023
- Голосувати за [пропозиції](https://smartsender.com/proposals) можуть всі користувачі з PRO-тарифом (Раніше було мін. 3 місяці активного тарифу)
- Додано швидке редагування дій/умов. Тепер не треба все заново вказувати, а лише змінити потрібну частину

### 01.11.2023
- Додано [Groups API](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1795457119/Groups+API+-+ua) (для LMS керування групами учнів) та [Contact Groups API](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1795784774/Contact+Groups+API+-+ua) (для LMS додавання/видалення групи у контакту)
- Додано [Trainings API](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1795751966/Trainings+API+-+ua) (для LMS керування тренінгами) та [Contact Trainings API](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1795751989/Contact+Trainings+API+-+ua) (для LMS додавання/видалення тренінгу у контакту)
- Додано [Definitions API](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1795915777/Definitions+API+-+ua) (керування глобальними змінними)
- Додано повідомлення про помилку html-форматування тексту в Telegram/Skype в редакторі воронки

### 31.10.2023
- Додано [Gates API](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1794965505/Gates+API+-+ua) (видалення/редагування повідомлень)
- Доповнено [Chats API](https://smartsendereu.atlassian.net/wiki/spaces/docsru/pages/1686175760/Chats+API+-+ua) (пошук, фільтр по статусу/оператору)

### 30.10.2023
- Додано пріорітетність сортування змінних (дозволяє важливі змінні відображати зверху списку)
- Додано папки для змінних, правил (для зручного сортування)

### 24.10.2023
- Додано можливість прикріплювати файл при відправці домашнього завдання в LMS (при наявності файлу текст не обов'язковий)
- Посилання в ДЗ в LMS автоматично стають клікабельними
- Розширені можливості коментарів до уроку LMS (глибина відповідей на коментарі, редагування, видалення, рейтинг)
- Додано можливість обмеження тесту LMS по часу
- Додавання сторонього відео в урок LMS розпізнає посилання на YouTube

### 06.10.2023
- Додано дії LMS у воронках (додати в групу/видалити з групи/ додати в тренінг/видалити з тренінгу). Працює за умови наявності пошти в системній змінній email
- Додано дії LMS в розділі "Контакти"
- Додано варінти умов LMS у воронках (участь в групі/участь в тренінгу/участь в уроці тренінгу)
- Додано копіювання тренінгів/груп LMS з шаблонами
