# Выгрузка данных из автоматизированного пайплайна сбора данных (через БД с поддержкой SQL), их предобработка для Tableau, соглвасование требований бизнес-заказчика и разработка дашборда в Tableau Public. Тренировочный проект.

## Симулируемая ситуация:
* Аналитик данных (протагонист проекта) еженедельно получает стереотипные вопросы от продуктового маркетинга о недельной сттистике активности пользователей интернет-портала Яндекс.Дзен.
* Принято решение о полной автоматизации сбора данных и предоставлении доступа продуктовому маркетингу к автоматически актуализируемым ответам на стереотипные вопросы по недельной статистике через дашборд в открытом доступе.
* Принято решение по технологическому стеку проекта:
 * пайплайн данных: log-files -> python-scripts (cron-scheduled) -> PostgreSQL,
 * автоматический запуск скриптов: планировщик задач cron,
 * средство разработки дашборд: Tableau Public.

## Цель проекта:
* Полная автоматизация - от журнальных файлов действий пользователя до дашборда с анализом данных в открытом доступе.

## Задачи проекта:
1. Разработка пайплайна сбора данных.
2. Автоматизация запуска скриптов при помощи планировщика задач.
3. Согласование ТЗ и макета дашборда с внутренним бизнес заказчиком.
4. Разработка дашборда и его публикация в открытом доступе.
5. Подготовка и проведение ознакомительной презентации возможностей дашборда.

## Статус проекта: ВЫПОЛНЕН

## Результаты проекта:
* Финальный дашборд доступен по ссылке
<a href='https://public.tableau.com/views/DashboardDA49SevastyanovAA/DashboardDA49SevastyanovAA?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link'>Dashboard on Tableau Public</a>.
* Детальное описание результатов проекта и самого дашборда доступно в виде презентации в данном фолдере проекта в формате pdf.