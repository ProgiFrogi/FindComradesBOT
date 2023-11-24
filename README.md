# Лабораторная работа 1 курса ВШПИ
## 1 семестр 2023 года

## Задача работы
### Этап 1
1. Придумайте телеграм-бот, который делает что-то полезное. Дайте ему имя, например My_bot.  
2. Бот должен иметь не меньше трех разных пользовательских юскейсов, то есть операций из одного или нескольких шагов, которые приводят к желаемому пользователем результату.
3. Опишите все возможные сценарии развития событий в боте по шагам в виде: промпт бота - варианты ответа пользователя - ответ бота - ... - финальный результат.
4. Создайте в этом репозитории директорию с именем "название бота - фамилия и инициал" (напр. mybot_ivanova_m). Хорошая культура работы в гит - не коммитить записи сразу в main, а до окончания работы создать свою ветку, которую замерджить в main только после финального review. 
5. Создайте в директории маркап файл с описанием сценариев бота.
6. Создайте телеграм-группу для тестирования бота методом "Механический турок". На время тестирования в группе переименуйте свой ТГ-эккаунт в "My_bot" (при желании можете зарегистрировать дополнительный ТГ-эккаунт с именем My_bot).

### Этапы 2.1 - 2.3
8. Пригласите для участия в тестировании испытателя. Попросите его провести испытание с одновременной аудиовидеозаписью. Для аудиовидеозаписи можно использовать видеоконференцию с записью (Zoom, Y-Телепорт и др.) или удаленный десктоп (рекомендуется RustDesk). Прямое согласие испытателя на запись и размещение в гитхаб записей испытания необходимо! 
9. Подключитесь вместе с испытателем к аудиовидеосессии и войдите в группу под именем My_bot.
10. Пишите в группу "от лица бота" сообщения, имитирующие промпты и ответы бота.
11. В процессе испытания внимательно наблюдайте за испытателем. Не вступайте с ним в общение, не подсказывайте, что ему делать (см. правила структурированного интервью ниже).
12. Когда испытание бота завершится, выйдите из роли "бота" и проведите с испытателем "контекстное структурированное интервью"
- по аудиовидеовязи обсудите с испытателем результаты своих наблюдений;
- попросите его рассказать о мыслях, впечатлениях, удачах и затруднениях;
- попросите описать и прокомментировать удачные и неудачные эпизоды общения с имитированным ботом.
13. По окончании скопируйте в текстовой файл историю сообщений группы, файл приобщите к гитхабу, а все сообщения в чате удалите. 
14. Проведите это испытание не менее чем с тремя разными испытателями.

### Этап 3 
16. Обобщите результаты интервью, определите 3 самых удачных и 3 самых проблемных места. 
17. Модифицируйте исходный сценарий бота, усилив удачные и заменив неудачные места. 
18. Напишите краткий (до 3000 знаков с пробелами) отчет, сопоставив сценарий до, сценарий после и дав статистику и резюме контекстных интервью.
19. Разместите в директории видеозаписи прошедших интервью (или разместите их как приватные видео на Ютубе и дайте в приложении к отчету ссылки на них). 


# Контекстуальное структурированное интервью
1. Цель интервью - наблюдать, а не объяснять. 
2. Содержание интервью: 
Вы даете пользователю перечень тестовых задач, которые вы просите его решить в системе. Задачи ставятся функционально - не "нажать кнопку", а "сохранить файл" и т.д. Это может быть как цепь шагов, так и несколько различных задач - смотря по функционалу системы. Разумеется, все участники интервью должны выполнять один и тот же тест, чтоб результаты были сравнимыми. Какой это будет тест - продумайте командой заранее. 
3. Порядок проведения: 
- Объясняете пользователю цель и правила игры.
- Пользователь выполняет тест, вы сидите рядом, смотрите, слушаете и фиксируете. 
- По окончании интервью вы докладываете пользователю свои выводы о достоинствах и недостатках и направлениях изменений в интерфейсе по мнению пользователя, КАК вы его поняли. Пользователь может внести изменения в эти выводы в меру своего представления о них. 
4. Пользователь - испытатель системы. Принципы его испытания:
- Он(она) должен(должна) быть не вашим приятелем или коллегой, а реальным потенциальным потребителем вашего решения. Чем меньше вы знакомы, чем меньше он похож(похожа) на вас, тем лучше. 
- Он(а) работает с системой так, как будто он(а) один(на), вас нет. 
- При этом он(а) должен(на) вслух комментировать и высказывать ("вербализировать") свои действия, чувства, мысли для вас. 
- Вы все это фиксируете молча, не огрызаясь, не оправдываясь и не бахвалясь. Вас нет. Вы учиться у пользователя пришли. 
5. Режим теста: 
- Вы можете переспрашивать, просить объяснить или развернуть сказанное, но не можете подсказывать. 
- Все непонятки пользователь преодолевает сам (или НЕ преодолевает, что служит для вас красным флагом). 
6. По окончании всех интервью вы их обобщаете и делаете выводы об общем и частном в этих интервью (если интервью было достаточно много, то и количественно), а на этой основе - вывод о следующей итерации изменений интерфейса. Что и выполняете.
