
# BlockchainSimulator

Web-based реализация концепта работы блокчейн от сената.


## Description

Это простое введение в концепции, лежащие в основе блокчейна. Мы представляем идею неизменяемой бухгалтерской книги, используя интерактивную веб-демонстрацию.


## FAQ

#### Раздел Hash

Позволяет генерировать hash на основе введенных в поле `Data` данных.

#### Раздел Block

Позволяет наглядно проследить за тем как подписываются блоки, как изменяется `Nonce` в зависимости от `Data`.

#### Раздел Blockchain

Показывает зависимость блоков друг от друга в цепи.

#### Раздел Distributed

Позволяет осознать принцип большинства в блокчейн.

#### Раздел Tokens

Отражает ключевую особенность блокчейна - защита данных благодаря неизменяемости, на примере финансовых операций.

#### Раздел Coinbase

Продолжение раздела `Tokens`, позволяющий учитывать наличие финансов у конкретных людей.


## Demo

Insert gif or link to demo

## Optional Configuration
Вы можете настроить количество нулей, требуемое демонстрацией, отредактировав первые две строки
`public/javascripts/blockchain.js`.

Поскольку в шестнадцатеричном значении содержится 16 возможных символов, каждый раз, когда вы увеличиваете сложность
на единицу, вы усложняете головоломку в 16 раз.

Если вы измените сложность выше 4, блоки будут отображаться как не добытые, потому что демонстрационные данные
предполагают 4 нуля для подписанного блока. Например, на `http://localhost:3000/block ` страница
со сложностью 6, первый работающий одноразовый номер - `8719932`, дающий хэш
`000000669445c22167511857d8f3b822b331c3342f25dfdcb326e35c1a7aa267`.

Вот некоторые оценки времени для различных пороговых значений.
|digits|nonce|time estimate|
|------|-------|-------------|
|4|500,000|15 minutes
|5|8,000,000|4 hours
|6|128,000,000|3 days
|7|2,048,000,000|a month
|8|32,768,000,000|2 years
|9|524,288,000,000|30 years
|10|8,388,608,000,000|481 years
|11|134,217,728,000,000|7,690 years
|12|2,147,483,648,000,000|123,036 years
|13|34,359,738,368,000,000|1,968,581 years
|14|549,755,813,888,000,000|31,497,291 years
|15|8,796,093,022,208,000,000|503,956,662 years

В блокчейне биткоина блок "458,091" имеет хэш-код
`00000000000000000000011246f099d94f91628d71c9d75ad2f9a06e2beb7e92`. Это 21 ноль подряд!
На добычу этого одного блока у майнера ушло бы примерно 8 454 989 768 407 765 лет.
## Authors

- [@clumzzzy](https://www.github.com/clumzzzy)
- [@khudysh](https://www.github.com/khudysh)
- [@oganesik](https://www.github.com/oganesik)
- [@v-golyadkin](https://www.github.com/v-golyadkin)
- [@Karen-mad](https://www.github.com/Karen-mad)

