Реализация генератора jndi-ресурсов для сервера Jetty. Следуя методологии SPI,
для обнаружения плагином данный jar должен быть помещен в classpath плагина.
Считается применяемым, если в конфигурации task плагина указать serverName = Jetty