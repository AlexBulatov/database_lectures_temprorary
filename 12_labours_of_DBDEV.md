Задания по разработке баз данных информационных систем

# 12 ПОДВИГОВ DBDEV

1. Информационная система контроля дипломов: студенты, документы, научруки, этапы выполнения
Подразумевает хранение в системе студентов и преподавателей, тему диплома и его состояние. Для диплома есть план выполнения, которого студент должен придерживаться. Помимо этого в системе хранятся документы по оформлению диплома и вся бюрократия для его сдачи. Диплом имеет текущий статус выполненности, процент выполнения по плану. При помощи системы научрук может контролировать ход выполнения дипломной работы: отправлять доработки, указывать недочёты и пр.

2. Библиотека: хранение списка книг, абонементы, забор книг, история пользования, поплнение полок
Обычная библиотека книг + снятие и контроль абонементов, взятых книг, история пользования книгами, задолженности по людям и пропавшие книги. Сведения о наличии книги в библиотеке через транзакцию в истории пользования и статусе возврата в ней. 

3. Приемная кампания университета: хранение документов, абитуриентов, списков, результатов экзаменов, электронная очередь и запись на подачу.
Имеются сущности абитуриентов, поданных дел, баллов ЕГЭ и результатов внутренних экзаменов, лиц, принимавших документы, сами документы абитуриентов. Помимо этого нужны сущности для электронной очереди и электронной подачи документов и отправки их в приемную комиссию.

4. Профориентация: списки профессий, списки направлений, компетенции, тесты, рекомендации

5. "Накопи на цель": банки, счета дебеты и счета откопления, транзакции. Пример - "Накопи на цель" Сбербанка

6. Клиника: пациенты, история болезни, врачи, записи, лекарства на складах, операции и пр.

7. ЖКХ: отслеживание задолженностей, отчёты, статусы по квартирам, аварийные случаи

8. Грузоперевозки UBER: заказы, контракты, перевозчики, груз
Хранение данных о грузчиках, их машинах и габаритах, грузоподъемности и пр. 

9. Заказ билетов (спросить Артёма): залы, места, стоимость, мероприятия

10. Организация мероприятий (спросить Сергея): конфенерц-залы, время, мероприятия, пользователи, участники

11. Студуслуги: оформление пропусков, документов, оплат долгов, библиотечных книг, вопросы в деканат и общежития
Регистрация на портале как студента со всеми необходимыми данными, заполнение информации об учебе, общаге, запрос на документы для пересдачи, оплаты общежития, регистрации и пр.. Заказ книг в библиотеке по списку, запросы в деканат и пр.

12.  Бонусы "Спасибо": акции, поставщики услуг, скидки, счета и банки, откопления, транзакции и пр.

13. ?Сеть кальянных: тут на ваше усмотрение и на усмотрение заказчика

14. ?Хэнд-Мейд ЖЫРА и конфлюенс (NoSQL, возможно на познать Tarantool): организация проекта, распределение задач, митапы, скрамы, бэклог проекта