Spring Security - это фреймворк предоставляющий средства для [[Авторизация|авторизации]] и [[Аутентификация|аутентификации]] в экосистеме [[Spring]] для [[Servlet Application|приложений на основе сервлетов]] и [[Web on Reactive Stack|реактивных приложений]].

## Основные модули и зависимости

### Core — `spring-security-core.jar`
Этот модуль содержит основные классы и интерфейсы аутентификации и контроля доступа и базовые API. Это необходимый модуль для Spring Security.

Основные пакеты:
- `org.springframework.security.core`
- `org.springframework.security.access
- `org.springframework.security.authentication`
- `org.springframework.security.provisioning`

![[Pasted image 20240222120410.png]]

### Remoting — `spring-security-remoting.jar`

Предоставляет интеграцию с Spring Remoting. 
Необходим для создания удаленного клиента, который использует Spring Remoting. Основной пакет - `org.springframework.security.remoting`.

### Web — `spring-security-web.jar`
