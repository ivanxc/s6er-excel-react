# s6er-excel-react
React приложение для проверки наличия автомобильного номера (тип 1) в excel таблице.
## Backend
Backend Java Spring Boot приложение [доступно здесь](https://github.com/ivanxc/s6er-excel-spring-boot).
## Интерфейс
1. Если номер введен не полностью, то он будет выделен красным на несколько секунд.<br/>
![ValueNotFilled](https://sun9-79.userapi.com/impg/n5-y7D04HjwgoXrs5o7T4moIgD2roAPk1YqThg/JB-W-IlLZMI.jpg?size=356x95&quality=96&sign=c8e893ff02f2e558e51ac57c5b8c2ce0&type=album)

2. Если номер найден в таблице, то он будет выделен зеленым на несколько секунд.<br/>
![FoundValue](https://sun9-85.userapi.com/impg/F0D_R8AO5A28UAcGOtuYBoE0sMwMpd7-1-Z7Bg/PCmtTrgkzhc.jpg?size=358x92&quality=96&sign=35296408273561622ab07a60934712f7&type=album)

3. Если номера не найдены, то ниже кнопки на несколько секунд появится текст "Номера не найдены".

:warning:**Так как backend работает на сервере с бесплатным тарифом, запросы могут выполняться несколько секунд!**
