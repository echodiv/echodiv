> The key point here is our programmers are Googlers, they’re not researchers. They’re typically, fairly young, fresh out of school, probably learned Java, maybe learned C or C++, probably learned Python. They’re not capable of understanding a brilliant language but we want to use them to build good software. So, the language that we give them has to be easy for them to understand and easy to adopt. – Rob Pike

## Main
```go
package main

import (
	"fmt"
	"strings"
)

var experience = []string{
	"golang", "python", "k8s", "rabbitMQ", "postgreSQL", "gRPC", "OpenAPI", "testing automation",
}

func main() {
	var (
		email    = "echodiv@outlook.com"
		telegram = "sergey_batalov"
	)

	fmt.Println("Hello World!")
	fmt.Printf("I am Sergey Batalov, software engineer with experience in %s\n", strings.Join(experience, ", "))
	fmt.Printf("Contact info: Email: %s, Telegram: %s\n", email, telegram)
}

```
## Experience
### Backend developer

- 03.2023 - current Yadro telecom<br />
🇷🇺 Saint Petersburg 

```
- Go
- RabbitMQ
- PostgreSQL
- k8s
- gRPC
```

- 01.2022 - 03.2023 Semrush<br />
🇷🇸 Belgrade <br/>
🇷🇺 Saint Petersburg 

Development of the server part of the data analytics service. Writing and optimizing Clickhouse queries.
```
- Go
- ClickHouse
- PostgreSQL
- k8s
- gRPC
```

- 06.2021 — 08.2021 Yandex Academy project<br />
🇷🇺 Moscow

```
- Python 3.9
- AIOhttp
- PostgreSQL
- Pytest
- Alembic
- SQLAlchemy
```

### QA automaion engineer

- 02.2021 — 05.2021 AT-Counsulting<br />
🇷🇺 Saint Petersburg 

Testing a complex web document management platform. Сreation of testing infrastructure.
```
- Python 3.5
- Selenium
- Requests
- Pytest
- SQL
- SOAP
```

- 08.2019 — 02.2021 Nexign<br />
🇷🇺 Saint Petersburg 

Testing PCRF component. Areas: diameter, REST, ldap backends. Make and edit LUA bundles for C++ tcp server. Write some python libraries with checkers.
```
- RobotFramework
- Python 2.7
- Oracle Database
- Ansible-playbook
- SQL
- LUA
```

## Education
Name | About
---- | -----
Saint-Petersburg State University of Aerospace Instrumentation (SUAI) 2014 - 2018 | Institute of Radio Engineering, Electronics and Communication Specialized in Instrumentation
Backend Development School at Yandex Academy 2021 | Completed the training and successfully defended the project (Python3.9, aiohttp, SQLAlchemy, PostgreSQL, alembic)
