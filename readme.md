| HTTP-Metod | Route      |
|------------|------------|
| GET        | /tweets    |
| CREATE     | /new       |
| PATCH      | /edit      |
| POST       | /new       |
| DELETE     | /delete    |
| GET        | /author:id |

**Validering:** Med hjälp av express-validator tvättas samt valideras all input innan det kan postas på servern genom att kolla ifall en användares author:id finns i datan innan den lägger upp en tweet på webbsidan.

**Extra funktioner:** Gällande extra funktioner så har jag bara lagt till sidorna about och contact, samt så har jag ändrat på bakgrunden och lite andra små detaljer i webbsidans utseende, men förutom det så har jag inte riktigt lagt till något.