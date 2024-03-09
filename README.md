# go-weather-cli

Learning go hands on with a simple weather cli app
```
> go run main.go

Bengaluru, India: 34⁰C, Partly cloudy
17:00 - 33⁰C, 0%, Sunny
18:00 - 31⁰C, 0%, Clear
19:00 - 30⁰C, 0%, Clear
20:00 - 30⁰C, 0%, Clear
21:00 - 27⁰C, 0%, Clear
22:00 - 26⁰C, 0%, Clear
23:00 - 24⁰C, 0%, Clear

> go run main.go mumbai

Mumbai, India: 34⁰C, Overcast
17:00 - 27⁰C, 0%, Sunny
18:00 - 27⁰C, 0%, Sunny
19:00 - 27⁰C, 0%, Clear
20:00 - 27⁰C, 0%, Clear
21:00 - 27⁰C, 0%, Clear
22:00 - 27⁰C, 0%, Clear
23:00 - 27⁰C, 0%, Clear
```

Run the build command
```
> go build main.go
```

Make it as executable after building

MacOS
```
> mv go-weather-cli /usr/local/bin
> go-weather-cli
```

Windows
```
> go build -o go-weather-cli.exe main.go

> go-weather-cli.exe

Bengaluru, India: 34⁰C, Partly cloudy
17:00 - 33⁰C, 0%, Sunny
18:00 - 31⁰C, 0%, Clear
19:00 - 30⁰C, 0%, Clear
20:00 - 30⁰C, 0%, Clear
21:00 - 27⁰C, 0%, Clear
22:00 - 26⁰C, 0%, Clear
23:00 - 24⁰C, 0%, Clear
```