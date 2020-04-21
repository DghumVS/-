Missing function access control - Доступ на http://localhost:5000/explore должен быть только у зарегистрированных пользователей, однако из-за некорректной настройки доступа, страницу видят любые пользователи.

SQL инъекция - На странице http://localhost:5000/search в поиске необходимо выполнить следующий запрос: first%' UNION ALL select id,username,password_hash,rights from user—

XSS - хранимый XSS на странице http://localhost:5000/explore
