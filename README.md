# lezytz2
# Food Delivery App
## Описание системы

Проектируемая система представляет собой мобильное приложение для заказа еды из ресторанов. Приложение позволяет пользователям просматривать меню различных ресторанов, заказывать блюда, оплачивать заказы онлайн и отслеживать статус доставки в реальном времени. Основные участники системы включают пользователей (клиентов), рестораны и курьеров.

Все диаграммы выполнены в [draw.io](https://app.diagrams.net/).

## [Диаграмма вариантов использования](

### Основные функции системы

Основные функции системы представлены в диаграмме вариантов использования:

- **Регистрация и авторизация пользователей**: Пользователи могут создавать учетные записи и входить в систему для персонализированного опыта, включая сохранение предпочтений и истории заказов.
- **Просмотр ресторанов и меню**: Пользователи могут искать рестораны по различным критериям и просматривать их меню.
- **Оформление заказа**: Пользователи могут выбирать блюда из меню, добавлять их в корзину, указывать количество и специальные запросы, а затем оформлять заказ.
- **Отслеживание заказа**: Пользователи могут отслеживать статус заказа на каждом этапе — от подтверждения ресторана до прибытия курьера.
- **Управление курьерами**: Курьеры получают уведомления о новых заказах, могут принимать или отклонять заказы и обновлять статус доставки.

## Диаграмма последовательности

Подробно рассмотрим действия основных участников системы, представленные в диаграмме последовательности для процесса заказа еды через приложение:

1. Пользователь открывает приложение, регистрируется или авторизуется и выбирает ресторан, где он хочет заказать еду.
2. Далее он заполняет корзину всем необходимым.
3. После чего он оплачивает заказ, который отправляется в ресторан и после подтверждения начинает собираться.
4. На всех этапах пользователь может отслеживать статус своего заказа.
5. После сборки заказа, его передают курьеру, и он доставляет заказ по указанному адресу.

## Диаграмма состояний заказа

Все состояния заказа можно посмотреть на диаграмме состояний заказа. На диаграмме видно, что при возникновении ошибок заказ будет отменен.

## Диаграмма деятельности

На диаграмме деятельности для описания процесса обработки заказа системой можно видеть, в какой последовательности приложение обрабатывает заказ.

## Диаграмма классов

На диаграмме классов представлены классы акторов, их свойства и методы. Эта диаграмма помогает визуализировать структуру системы и взаимодействие между различными объектами.

---

Эта система предназначена для упрощения процесса заказа еды и обеспечения удобного и качественного сервиса для всех участников — пользователей, ресторанов и курьеров.
