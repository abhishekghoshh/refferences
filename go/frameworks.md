# Frameworks for go

- Gin Web Framework: This is the most popular web development library for Go, and for a number of good reasons.(<https://gin-gonic.com/>)
- Beego is a full-stack web framework for building web applications and services. It provides a range of features and tools for developing web applications quickly and easily. (<https://beego.vip/>)
- Echo: This framework supports RESTful API design and is the most popular Go microservices framework.(<https://echo.labstack.com/guide/>)
- go-micro: This library is another great option in the same realm with built-in authentication and data storage designs. Quite handy indeed.(<https://github.com/go-micro/go-micro>)
- Gorilla Mux is a powerful URL router and dispatcher for Go that provides a flexible and intuitive API for routing HTTP requests in web applications. (<https://github.com/gorilla/mux>)
- Buffalo is a full-stack web development framework for building web applications and services. It provides a range of tools and features for developing web applications with Go. (<https://gobuffalo.io/#>)
- Goji is a minimalist web framework for Go that is designed for building APIs and microservices. It has a lightweight design and focuses on simplicity and performance. Goji comes with features such as routing, middleware, and request handling that make it easy to build APIs and is a popular choice among Go developers who want a fast and efficient framework. (<https://goji.io/>)
- The fasthttp framework provides a fast HTTP server and client API which was made as an alternative to net/http due to its limits on optimization opportunities. It is optimized for speed and can easily handle more than 100K qps and more than 1M concurrent keep-alive connections on modern hardware. It is also optimized for low memory usage and provides easy connection upgrade support via RequestCtx.Hijack. (<https://github.com/valyala/fasthttp>)
- Revel is a high-performance web framework for building APIs and web applications. It offers a simple and flexible API for developing web applications with Go. (<https://revel.github.io/>)
- Iris Web Framework: This is also another option for building high-performance web applications and APIs in Go. If you’ve worked with ExpressJS before, this will feel slightly familiar. (<https://www.iris-go.com/>)
- kit framework is a programming toolkit for building robust, reliable, and maintainable microservices in Golang. It is a set of packages and best practices, which provide a comprehensive, robust, and trustable way of building microservices for organizations of any size. Go is a great general-purpose language, but microservices require a certain amount of specialized support. (<https://github.com/go-kit/kit>)
- Go-Protobuf is a Protocol Buffers library for Go that provides a simple and straightforward API for encoding and decoding Protocol Buffers messages in Go. (<https://github.com/golang/protobuf>)
- Gorm: This is the easiest to use object relational mapping (ORM) Go library I’ve had the pleasure of using with three major kinds of databases SQLite, PostgreSQL, and MySQL.(<https://github.com/go-gorm/gorm>)
- Go-SQLite3 is a SQLite3 driver library for Go that provides a simple and straightforward API for working with SQLite3 databases from Go. (<https://github.com/mattn/go-sqlite3>)
- Go-redis: This is a great, highly maintained redis database client for Go. It works with both redis 6 and 7 and has a phenomenally easy setup process. Highly recommended.(<https://github.com/go-redis/redis>)
- go-elasticsearch — This is the official Elasticsearch client for Go. (<https://github.com/elastic/go-elasticsearch>)
- graphql-go: This is an implementation of GraphQL in Go and supports queries, mutations & subscriptions. (<https://github.com/graphql-go/graphql>)
- Hugo: A great package that lets you build static websites without backend interconnections, all written in Go. (<https://github.com/gohugoio/hugo>)
- Viper: This is a complete configuration solution for Go applications including 12-Factor apps. (<https://github.com/spf13/viper>) It is designed to work within an app, and can handle all types of configuration needs and formats.Some neat features from this package include:
  - reading from JSON, TOML, YAML, HCL, .env, and Java properties config formats
  - live watching and re-reading of config files
  - reading from environment variables
- GoDotEnv: It boasts the easiest setup and usage for reading variables from .env files, and is quite lightweight in use too. (<https://github.com/joho/godotenv>)
- Cobra: A powerful library for creating Go based CLI applications.(<https://github.com/spf13/cobra>) Some great features from this framework include:
  - It has a powerful integration with the Viper library for config files
  - It has support for regular subcommands, nested subcommands, and helps in grouping similar commands
  - Fully POSIX-compliant flags (including short & long versions)
- Task: This library boasts more verbosity and thus, slightly better explainability for executing commands than Make. (<https://taskfile.dev/>) It also has no dependencies and is quite lightweight in comparison.Automation tool that aim to help execute tasks with a simple, concise command.One popular tool that you might already know is the Make command, that helps us use the task automation with Makefiles. A good development practise is to keep a list of commands to execute defined in a Makefile, which we can easily reference later on and execute with simple make commands.
- Air: This is a great utility Go package that helps rebuild and execute the project’s main.go on save or virtually any files on save (as we want it) without us typing it out to run it every single time. (<https://github.com/cosmtrek/air>)
- Carbon: This is a great lightweight, easy to use, and semantically intelligent datetime library for Go developers.(<https://github.com/golang-module/carbon>)
- Colly: This is a wonderful web scraper and crawler framework for Go, especially useful for archiving (which I’ve heavily used it for) and data mining purposes. (<https://github.com/gocolly/colly>)


## Dependency links
- https://github.com/spf13/viper/
- https://gorm.io/docs
- https://github.com/jmoiron/sqlx/
- https://github.com/golang/mock