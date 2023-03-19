 Training dashboard carried out as part of the training on the Data Analysis сourse at Yandex.Practicum and other educational programs

## Unicorn companies dashboard

Link to the dashborad (Tableau Public):
https://public.tableau.com/views/UnicornCompanies_16785247614320/Dashboard3?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Данные о компаниях-единорогах (https://disk.yandex.ru/i/Qdyir2rq2hydsg). Компании-единороги - это частные компании, стоимость которых превышает 1 млрд. долларов по 
состоянию на 1 января 2023 г. Данные включают текущую оценку стоимости каждой  компании, размер привлеченных инвестиций, страну, в которой зарегистрирована компания, 
отрасль, в которой работает компания-единорог, компании-инвесторы, годы, в которые  компания привлекла инвестиции и когда стала единорогом, описание деятельности, ссылки 
на сайт, адреса, стадии инвестирования. 
Источники данных: https://www.cbinsights.com/research-unicorn-companies и 
https://news.crunchbase.com/unicorn-company-list/

### Описание полей:
Unicorns:
* Company - название компании
* Valuation (B) - оценка стоимости компании, млрд. долларов
* Date Joined - дата, когда компания стала единорогом
* Country - страна регистрации компании
* City - город регистрации компании
* Continent - континент регистрации компании
* Industry - отрасль, в которой работает компания
* Select Investors - инвесторы, которые проинвестировали команию, перечислены через запятую
* url - адрес веб-сайта компании
* founded_year - год основания компании
* stage - раунд инвестирования, на котором находится компания
* total_funded - размер инвестиций в компанию, млрд. долларов 
* description - описание деятельности компании
* hq_address - адрес главного офиса

Investors:
* Company - название компании
* Select Investors - инвесторы, которые проинвестировали команию, каждый инвестор — в 
отдельной строкe
