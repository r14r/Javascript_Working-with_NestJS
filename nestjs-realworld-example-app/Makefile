default:
	cat Makefile

mssql-cli-install:
	npm install -g sql-cli

mssql-install:
	docker pull microsoft/mssql-server-linux

mssql-run:
	docker run -d --name sql_server_demo -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=reallyStrongPwd123' -p 1433:1433 microsoft/mssql-server-linux

mssql-connect:
	mssql -u sa -p reallyStrongPwd123


install:
	npm install

run:
	npm run start:dev
