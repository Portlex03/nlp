Используя публичный API сайта HeadHunter (особое внимание на метод https://api.hh.ru/vacancies/) необходимо:

- скачать минимум 200 вакансий по заданному ключевому слову (можете задать слова, характеризующие профессии в IT); если вакансий менее 200 - скачать все, что есть;

- предобработать каждую вакансию (очистить от тегов и специальных символов, токенизировать, нормализовать любым из двух способов, удалить стоп-слова);
- сохранить все полученные вакансии (список списков токенов) на диск (Google Drive) с помощью pickle.

Выполняя данное дополнительное задание вы можете поиграться с многопоточностью в Python и организовать загрузку информации о вакансиях в параллельном режиме.
