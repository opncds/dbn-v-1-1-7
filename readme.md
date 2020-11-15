## ДБН В.1.1-7 Пожежна безпека об’єктів будівництва

У цьому репозиторії зібрано, структурувано та виправлено формат даних офіційного документа [ДБН В.1.1-7:2016 Пожежна безпека об’єктів будівництва](https://www.minregion.gov.ua/wp-content/uploads/2017/03/DBN-V.1.1-7-2016.pdf), який опублікований на сайті [Міністерство розвитку громад та територій України](https://www.minregion.gov.ua/napryamki-diyalnosti/building/tech-reg/normuvannia/derzhavni-ta-galuzevi-budivelni-normi/) але не відповідає вимогам, щодо  оприлюдненню у вигляді відкритих даних.

#### Кроки по виправленню формату данних докуента:
- [x] [конвертація неструктурованого PDF у структорований Markdown документ](dbn-v-1-1-7.md);
- [x] декодування з Cyrillic Windows-1251 до UTF-8;
- [ ] відокремлення положень ДБН та агрегація у [єдиному для всіх документів сервісі документації](https://github.com/opncds/open-codes);
- [ ] забезпечення посилання на пов'язані норми та положення норм даного та інших документів, додатків до документу
- [ ] конвертація структурованих данних в окремі докуенти JSON, CSV

_Розміщені у репозиторії документи (електронні файли різних форматів), 
незважаючи на їх автентичність з оригіналами (друкованими чи віртуальними виданнями), 
носять інформаційно-довідковий характер (для некомерційної діяльності) 
і не мають статусу офіційних._

Метою є створення прототипу, який би наглядно демонстрував необхідний функціонал платформи для роботи з текстом положеннь будівельних норм.

#### Ключові вимоги до формату даних положень Державних та галузевих будівельних норм:
- [ ] оприлюднення текстів документів у повному обсязі;
- [ ] наявність структури документу (навігація за окремими положеннями);
- [ ] оприлюднення текстів документів у контрольному стані (актуалізація документу в останній редакції із внесеними змінами);
- [ ] забезпечення версійності документу, в тому числі майбутніх редакцій документа;
- [ ] забезпечення посилання на пов'язані норми та положення норм даного та інших документів, додатків до документу;
- [ ] забезпечення повнотекстового пошуку в документах;
- [ ] можливість друку та експорту документа в форматі “PDF”, “DOC”, “HTML”;
- [ ] публікація структурованих даних окремими документами (RDF, XML, JSON, CSV, XLS(X), ODS, YAML)
- [ ] забеспечення спільного блоку термінів і понять
