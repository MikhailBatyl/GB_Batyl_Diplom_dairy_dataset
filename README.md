#   Анализ продаж молочной продукции и оптимизация управления запасами на молочных фермах

***СТАТУС:*** **Выполнено**

## *Цель проекта:* 

  Изучить особенности анализа данных по продажам молочной продукции и оптимизация складских запасов. Способы формирования интерактивных дашбордов в целях автоматизации процессов на производстве.

## *Задачи:* 

  Изучить литературу, материалы и статьи касающиеся темы анализа продаж, общая эффективность производства, маркетинговые исследования.
Рассмотреть несколько вариантов имеющихся платформ для создания дашбордов, обработки данных и выбрать ПО соответствующее задачи автоматизации.
Произвести анализ эффективности молочных ферм с учетом местоположения, площади земель и поголовья коров.
Сформировать модель продаж и распределения различных молочных продуктов по различным брендам и регионам.
Оптимизировать управление запасами путем отслеживания количества запасов, минимальных пороговых значений и количества повторных заказов.
Разработать прогнозную модель для прогнозирования спроса и стратегий ценообразования.
Разработать дашборд, отражающий результаты анализа данных по продажам и запасам, позволяющий вручную оптимизировать рекомендуемые объемы и ассортимент заказа производителя.

## *Инструменты:* 

GitHub, VScode, Power BI, Power Query, DAX, Python, MS Office, draw i и др.

## *Структура дипломного проекта:* 

## Оглавнение:

## Введение 

На рынке прогнозируется уменьшение количества поставщиков молочной продукции, падение их производительности в связи со сложной экономической ситуацией, сезонным снижением цен в летний период и неутешительными для поставщиков прогнозами падения цен на сырье осенью. Небольшие поставщики, вероятно, не смогут обеспечивать поставку сырья на прежних условиях. Как сохранить прежних поставщиков, а в случае с новыми, наладить сотрудничество и предложить оптимальные условия работы и оплаты за сырье?
Чтобы гибко реагировать на изменение покупательского спроса, предприятиям важно отслеживать потребности рынка и периодически менять ассортимент. В сложных экономических условиях это становится как никогда актуальным, поскольку повышается риск того, что выпущенная продукция не будет продаваться, что приведет к затовариванию складов и потере денег — ведь молочная продукция в основном имеет короткий срок годности и, следовательно, необходимо своевременно ее реализовывать. 
Проанализировать покупательский спрос и вовремя пересмотреть стратегию продаж поможет аналитика с классификацией по продажам продукции как по наименованиям (видам), так и по регионам поставки и сегментам. Руководителям отделов продаж (сбыта) и менеджерам по продажам в настоящее время важно анализировать потребности покупателей именно своего региона, поскольку на полках магазина, чаще всего и представлена продукция местных производителей.
Таким образом, используя аналитические отчеты, руководители предприятия могут получать необходимую для анализа информацию и своевременно принимать решение о выпуске наиболее востребованной и приносящей прибыль продукции.
На фермах и молокоперерабатывающих предприятиях выпуск продукции осуществляется под заказы клиентов. Как правило, это постоянные клиенты и спрос у них более-менее стабильный, поэтому производству понятно: что производить и в каком количестве. Но, даже у постоянных клиентов могут изменяться планы по количеству и ассортименту закупаемой продукции и эти колебания необходимо отслеживать, чтобы своевременно скорректировать планы производства. Для решения этой задачи начальник производства и сотрудники планового отдела могут использовать инструменты планирования производства и расчета потребностей в материалах с учетом отраслевой специфики. Программа поможет рассчитать, когда и сколько сырья и материалов (в зависимости от их качества) потребуется на выпуск продукции в соответствии с планами производства, а также запланировать выпуск полуфабрикатов.
Немаловажная задача — это обеспечение полной загрузки производственных мощностей. Ведь потери от простоев оборудования для заводов могут быть критичными. 
В период, когда предприятия стремятся оптимизировать расходы, становится буквально обязательным не только своевременно отгружать продукцию, но и выстраивать маршруты автомобилей, развозящих продукцию клиентам так, чтобы максимально сократить затраты на доставку.
Цифровизация всех бизнес-процессов — неизбежное будущее ферм молокоперерабатывающих предприятиях, ферм, а своевременная, корректная аналитика поступающих данных, снижает риски в части принятия неверных действий, шагов оптимизации бизнеса.
Цифровая трансформация – глубокая реорганизация бизнес-процессов с широким применением цифровых инструментов для их исполнения, которая приводит к существенному улучшению их характеристик (сокращение времени выполнения, исчезновению целых групп подпроцессов, сокращению ресурсов, затрачиваемых на выполнение процессов) и/или появлению принципиально новых их качеств и свойств.
Результаты автоматизации и цифровизации в виде внутренних автоматизированных и прошедших реинжиниринг процессов, внедренных автоматизированных систем и надежных данных, во многих случаях служат основой для цифровой трансформации.


## Глава 1. Основы автоматизации процесса, связанных с аналитикой данных

1.1. Что такое автоматизация бизнес-процесса

1.2. Какой бизнес нужно автоматизировать

1.3. Какие требования существуют к автоматизации процесса

1.4. Способы сбора и анализа данных 

1.5. Что такое дашборд. Как он может повысить эффективность аналитических процессов

## Глава 2. Подготовка к разработке дашборда 

2.1. Сбор требований к разработке дашборда

2.2. Сбор и обработка данных для анализа бизнес-процесса продажи молочных товаров

2.3. Сформировать список отслеживаемых метрик, необходимых для автоматизации, разработки дашборда

2.4. Составить предварительную визуализацию дашборда

2.5. Создать модуль обработки и анализа данных, а также протестировать его на данных компаний по производству молочной продукции

2.6. Произвести анализ предпочтений и покупательского поведения клиентов в зависимости от местоположения и каналов продаж

2.7. Изучить влияние условий хранения и сроков годности на качество и доступность молочной продукции

2.8. Провести маркетинговые исследования ABC-анализ продаж

## Глава 3. Описание процесса создания системы

3.1. Разработка дашборда 

3.2. Подведение итогов. Разработка предложений по улучшению процесса продаж и оптимизации производства


## Вывод исследования:

1. Бизнес выводы ABC-анализа продаж:
   
Группа А – самые важные ресурсы, приносят максимальную прибыль и продажи. Компания будет нести большие потери при резком снижении эффективности данной группы ресурсов, а следовательно, ресурсы группы А должны жестко контролироваться, четко прогнозироваться, часто мониториться, быть максимально конкурентоспособными и не терять свои сильные стороны. На данную группу ресурсов должны быть выделены максимальные инвестиции, лучшие ресурсы. Успехи группы А должны быть проанализированы и максимально транслироваться на другие категории.

Группа В – группа ресурсов, которые обеспечивают хорошие стабильные продажи/ прибыль компании. Данные ресурсы также важны для компании, но могут модерироваться более спокойными и умеренными темпами. Данные ресурсы относительно стабильны в краткосрочной перспективе. Инвестиции в данный вид ресурсов компании не значительны и необходимы только для поддержания существующего уровня.

Группа С – наименее важная группа в компании. Обычно ресурсы группы С тянут компанию вниз или не приносят дохода. При анализе данной группы необходимо быть очень внимательным и в первую очередь понять причину низкого вклада.

Дополнительно:

Группа AAA - посмотреть XYZ-анализ, чтобы принять решение о поднятии цены и увеличение объема производства. Если группа X - можно поднимать цену на короткий период, чтобы увеличить маржинальность. Тестем в течение небольшого срока, чтобы оценить динамику продаж. Если группа Y/Z, лучше не увеличивать цену, потому что сложно будет оценить влияние. Лучше понять, почему спрос нестабильный. И либо поднять цену, но аккуратно спланировать эксперимент на более длинный срок, либо не повышать цену.

Группа ССA - оценить объективность причин, часть вывести из ассортимента, попробовать перевести в группу повыше по количеству (а может и по выручке за счет этого). Объективность причин - проверить качество, не просроченный ли он и др.
Подтянуть в группу B по количеству можно за счет акции 1+1 или 2+1 даже, как вариант. Можно увеличить средний чек и количество продаж за счет такой акции, стимулируя покупать больше и др. варианты.

Группа AAB - нужно просто найти более выгодную цену поставки, чтобы стать AAA. Либо попробовать немного подтянуть цену, если это группа X по XYZ-анализу. 

Группа ABA - судя по всему, нужно увеличить количество продаж, не упав в прибыли, плюс реализовывать объем производства, сокращать складские остатки. Можно попробовать постепенно, сделать акцию формата 1+1 или другой вариант акции. Ищем другого поставщика или сбиваем цену у текущего, чтобы увеличить прибыль.
 
3. Подведение итогов. Разработка предложений по улучшению процесса продаж и оптимизации производства.
   
   Вывод: после проделанного анализа, сформировал следующие предложения по улучшению процесса продаж и оптимизации производства.
   
2.1.	Расширить информацию в датасете, добавить дополнительные показатели. Например, отслеживать объем производства и количество остатков на конец периода (месяц), фиксировать какой объем перешёл на следующий период, сколько ушло в отходы (потери), рассчитывать стоимость потерь, типа перепроизводство, дополнительные затраты. 

2.2.	Осуществлять постоянный, оперативный мониторинг показателей, один раз в квартал производить ABC-анализ по продуктовой группе и XYZ -анализ, по итогу производить корректировку в планирование производства, модель продаж.

2.3.	Разработать модель продаж, согласно стратегическому планированию (прогноз не менее одного года).

2.4.	Сократить объем Reorder Quantity (liters/kg) рекомендуемое количество молочного продукта для повторного заказа, до показателей Minimum Stock Threshold (liters/kg) минимальный порог запаса молочного продукта. Минимизировать показатель «упущенная выгода», сформировать программу по сокращению складских остатков.

2.5.	Для сокращения складских остатков, необходимо разработать дорожную карту по выходу на внешний рынок, расширить территорию продаж продуктовой группы, в первую очередь использовать продукцию из группы B и C (из ABC-анализа).

2.6.	Осуществлять контроль производственной программы, в рамках одного периода, (например, в течение одного месяца), разработать стратегическое планирование производства. Для данного типа продукции, с минимальным сроком годности и небольшим временем производства, складские остатки должны быть минимальные, близкие к нулю, производство - отгрузка – продажа. Формировать плановые показатели, производить сравнение с фактическими, отслеживать динамику, в течение определенного периода времени (один месяц).

2.7.	Сформировать модель продаж, изменить подход к продажам, пересмотреть КПЭ сотрудников отдела продаж.

2.8.	Отслеживать динамику, делать анализ продаж и потребности конечных заказчиков, а также формирование складских остатков.

2.9.	Пересмотреть концепцию стоимости продуктовой группы, где возможно повысить стоимость, начать процесс корректировки, взять за базовый уровень (доходная часть/маржинальный доход). В случае, где стоимость была ниже прайса, провести аудит процесса, определить узкие места, проблемы, это может быть переизбыток продукта на рынке, высокая конкуренция, неэффективная работа отдела продаж, неграмотное ценообразование. Выявить причину, почему в некоторой группе продуктов, требуется постоянно давать скидки, а по остальной части продавать дороже. В итоге, общая картина по доходу компенсируется, потери на длительном промежутке (допустим в рамках одного года) времени не заметны, а итоговые (факт) показатели выравниваются относительно прогноза (плановые). Произвести оценку стоимости конкурентов. Перспектива на развитие имеется как со стороны производства, так и со стороны отдела продаж. В дальнейшим делать контроль соблюдения ценовой политики, соблюдение прайса, в случае отклонения фиксировать причину. 

2.10.	В общем, каждый год присутствуют потери по факту окончания календарного (финансового) года. Необходимо сделать обследование производства, организовать операционную трансформацию на производстве. А также, повторно, запустить проект по стратегическому планированию и разработать прогнозную модель продаж. Проводить SWOT- анализ, поможет дать объективную оценку деятельности компании.

2.11.	 В ходе проведения аналитики, наблюдаем большое количество выбросов в датасете, необходимо дополнительно фильтровать данные.


Список используемой литературы   
Приложения
