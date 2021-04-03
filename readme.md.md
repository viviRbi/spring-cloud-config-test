# Spring Cloud Config from a Remote Git

- Use Spring Boot project starter, add Spring Colud Config Server to the initilize project
- Add application.yml file
- Declare the port, git repo, username and password if needed, and search pattern
- Url:
	- http://localhost:8889/s1rates/master or /default(main app file + s1rates file - because we have set the search pattern to look inside this folder)
	- http://localhost:8889/whatever/default or /master(main application file)
	- http://localhost:8889/whatever/dev (return main app, s1rates, s1rates dev)
	- http://localhost:8889/s1rates-default.properties (return s1rates + application all in 1 properties file)
	- http://localhost:8889/s1rates-dev.json (return app, s1rates, s1rates dev all in 1 json file)
