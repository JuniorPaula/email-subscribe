# Email subscribe in Golang

This is a simple web application that to send email using **Golang**.
This application using `cuncurrency` to send all emails.

## Requirements
- go
- docker
- docker compose
- Makefile

## Quick Start
```cmd
docker-compose up -d
```
```cmd
make start
```

## Some features
- signup user 
- validation signup via email
- email subscriber

## Tests
```cmd
go test ./cmd/web -v .
```
```
=== RUN   Test_Pages
--- PASS: Test_Pages (0.00s)
=== RUN   TestConfig_PostLoginPage
--- PASS: TestConfig_PostLoginPage (0.00s)
=== RUN   TestConfig_SubscribeToplan
--- PASS: TestConfig_SubscribeToplan (5.01s)
=== RUN   TestConfig_AddDefaultData
--- PASS: TestConfig_AddDefaultData (0.00s)
=== RUN   TestConfig_IsAuthenticated
--- PASS: TestConfig_IsAuthenticated (0.00s)
=== RUN   TestConfig_render
--- PASS: TestConfig_render (0.00s)
=== RUN   Test_Routes_Exists
--- PASS: Test_Routes_Exists (0.00s)
PASS
ok  	subscription-service/cmd/web	5.021s
`