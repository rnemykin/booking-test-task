# booking-test-task

Требуется разработать сервис(веб сервис, без фронта) бронирования ресурсов (Resource).
Ресурс описывается полями id, name, type (resource-service)

Бронирование может осуществить пользователь, который есть в системе.
Пользователи должны хранится и обрабатываться в отдельном сервиса (user-service) 
и взаимодействовать с другими через Rest API.

Бронирование имеет:
 - ссылку на ресурс, 
 - время бронирования, 
 - время окончания бронирования, 
 - данные о пользователе, который резервирует ресурс.
 
Одновременно ресурс могут бронировать несколько пользователей, система должна корректно обрабатывать этот кейс и сделать только одно бронирование в заданный интервал.

## Технический стэк
 - Spring Boot
 - Spring Data
 - Spring Web / Webflux
 - Java 8+
 - СУБД - любая
