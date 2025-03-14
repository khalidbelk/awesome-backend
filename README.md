<div align="center">
    <h1>Awesome Backend</h1>
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome">
    <br><br>
    <p>A curated list of awesome backend tools, libraries and resources.</p>
</div>

<br>

- [Runtimes & Frameworks](#runtimes--frameworks)
- [Databases](#databases)
- [ORM's & ODM's](#orms--odms)
- [Testing](#testing)
- [Monitoring](#monitoring)
- [Documentation](#documentation)
- [Devops & CI / CD](#devops--ci--cd)
- [Architectures & Design Approaches](#architectures--design-approaches)
- [Other tools](#other-tools)

----------

### Runtimes & Frameworks

**Javascript / Typescript**
- [NodeJS](https://github.com/nodejs/node) : a cross-platform, open-source JavaScript runtime environment.
- [Bun](https://github.com/oven-sh/bun) : a JavaScript runtime, package manager, test runner and bundler (alternative to Node.js).
- [Deno](https://github.com/denoland/deno) : a JavaScript, TypeScript, and WebAssembly runtime with secure defaults and a great developer experience.
- [Nitro](https://github.com/nitrojs/nitro) : a lightning-fast server engine eupercharging web development. 
- [Elysia](https://github.com/elysiajs/elysia) : a high-performance Node.js web framework built on Bun with end-to-end type safety.
- [ExpressJS](https://github.com/expressjs/express) : a fast, unopinionated, minimalist web framework for Node.js.
- [AdonisJS](https://github.com/adonisjs/core) : a TypeScript-first web framework for building web apps and API servers.
- [Fastify](https://github.com/fastify/fastify) : a fast and low overhead web framework, for Node.js.
- [NestJS](https://github.com/nestjs/nest) : a framework for building efficient, scalable Node.js server-side applications.

**C#**
- [Microsoft ASP.NET Core](https://github.com/dotnet/aspnetcore) : a cross-platform .NET framework for building modern cloud-based web applications on Windows, Mac, or Linux.

**Ruby**
- [Rails](https://rubyonrails.org/) : a server-side web application framework written in Ruby.

**Python**
- [Django](https://www.djangoproject.com/) : a high-level Python web framework that encourages rapid development and clean, pragmatic design.
- [FastAPI](https://github.com/fastapi/fastapi) : a modern, fast (high-performance), web framework for building APIs with Python based on standard Python type hints

**Rust**
- [Shuttle](https://github.com/shuttle-hq/shuttle) : fastest way to build & ship a backend without writing any infrastructure files in Rust.
- [Rivet](https://github.com/rivet-gg/rivet) : an open-source solution for deploying, scaling, and operating multiplayer game servers and backend services.
- [Axum](https://github.com/tokio-rs/axum) : an ergonomic and modular web framework built with Tokio, Tower, and Hyper in Rust.
- [Actix](https://github.com/actix/actix-web) : a powerful, pragmatic, and extremely fast web framework for Rust.

**Java**
- [Spring Boot](https://github.com/spring-projects/spring-boot) : a tool that makes developing web applications and microservices with Java Spring Framework faster and easier.

**PHP**
- [Laravel](https://github.com/laravel/laravel) : a free and open-source PHP-based web framework for building web applications.
- [Symfony](https://github.com/symfony/symfony) : a set of reusable PHP components and a PHP framework to build web applications, APIs, microservices and web services.
- [CakePHP](https://github.com/cakephp/cakephp) : an open-source web, rapid development PHP framework that makes building web applications simpler, faster and require less code.

**Other**
- [AppWrite](https://github.com/appwrite/appwrite) : an open-source platform for building applications at any scale, using your preferred programming languages and tools.
- [Gin](https://github.com/gin-gonic/gin) : A high-performance HTTP web framework written in Go, known for its speed and minimalist design.
- [Phoenix](https://www.phoenixframework.org/) : a web framework for the Elixir programming language that gives you peace of mind from development to production.

### Databases

**Relational Databases**

- [PostgreSQL](https://github.com/postgres/postgres) : a free and open-source relational database management system (RDBMS) emphasizing extensibility and SQL compliance.
- [SQLite](https://www.sqlite.org/) : a free and open-source relational database engine written in the C programming language.
- [CockroachDB](https://github.com/cockroachdb/cockroach) : a distributed database with standard SQL for cloud applications.
- [MySQL](https://www.mysql.com) : an open-source relational database management system.
- [MariaDB](https://github.com/MariaDB/server) : a community-developed, commercially supported fork of the MySQL relational database management system.

**Document-Oriented Databases**

- [MongoDB](https://github.com/mongodb/mongo) : an open-source, document-oriented database management system.
- [Apache CouchDB](https://github.com/apache/couchdb) : an open-source document database that collects and stores data in JSON-based document formats.

**Analytical Databases**

- [DuckDB](https://github.com/duckdb/duckdb) : a high-performance analytical database system. It is designed to be fast, reliable, portable, and easy to use.
- [Apache Druid](https://github.com/apache/druid/) : a high performance, real-time analytics database that delivers sub-second queries on streaming and batch data at scale and under load.
- [Apache Pinot](https://github.com/apache/pinot) : a real-time distributed OLAP datastore, purpose-built to provide ultra low-latency analytics at extremely high throughput.

**Other Databases**

- [Redis](https://github.com/redis/redis) : an open-source, in-memory, key-value store that is used primarily as an application cache or quick-response database.
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) : a managed NoSQL database service provided by AWS that supports key-value and document data structures.
- [Cassandra](https://cassandra.apache.org/_/index.html) : a distributed NoSQL database that delivers continuous availability, high performance, & linear scalability.

**DB Tools**
- [PgAdmin](https://github.com/pgadmin-org/pgadmin4) : a web based administration tool for the PostgreSQL database.
- [DB Browser for SQLite](https://sqlitebrowser.org/) : a high quality, visual, open-source tool designed for people who want to create, search, and edit SQLite or SQLCipher database files.
- [DBeaver](https://github.com/dbeaver/dbeaver) : a free cross-platform database tool for developers, database administrators, analysts, and everyone working with data.
- [MongoDB Compass](https://github.com/mongodb-js/compass): a powerful GUI for querying, aggregating, and analyzing your MongoDB data in a visual environment


### ORM's & ODM's

**ORM's (Object Relational Mapping)**

- [Drizzle](https://github.com/drizzle-team/drizzle-orm) : a lightweight and performant TypeScript ORM with developer experience in mind.
- [Prisma](https://github.com/prisma/prisma) : next-generation ORM for Node.js & TypeScript.
- [TypeORM](https://github.com/typeorm/typeorm) : an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES2021).
- [Sequelize](https://github.com/sequelize/sequelize) : a modern TypeScript and Node.js ORM for Oracle, Postgres, MySQL, MariaDB, SQLite and SQL Server, and more.
- [MikroORM](https://github.com/mikro-orm/mikro-orm) : a TypeScript ORM for Node.js based on Data Mapper, Unit of Work and Identity Map patterns.

**ODM's (Object Document Mapping)**

- [Mongoose](https://github.com/Automattic/mongoose) : a MongoDB object modeling tool designed to work in an asynchronous environment.
- [Beanie](https://github.com/BeanieODM/beanie) : an asynchronous Python object-document mapper (ODM) for MongoDB.
- [MongoEngine](https://github.com/MongoEngine/mongoengine) : a Python object data mapper for MongoDB.

**Query builders**
- [Kysely](https://github.com/kysely-org/kysely) : a type-safe and autocompletion-friendly TypeScript SQL query builder.
- [Diesel](https://github.com/diesel-rs/diesel) : a safe, extensible ORM and query builder for Rust.

### Testing

**API testing**

- [Postman](https://www.postman.com/) : a platform for collaborative API development.

**Unit tests** :

- [Jest](https://github.com/jestjs/jest) : a delightful JavaScript Testing Framework with a focus on simplicity.
- [Mocha](https://github.com/mochajs/mocha) : a feature-rich JavaScript test framework running on Node.js and in the browser.
- [Chai](https://github.com/chaijs/chai) : a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
- [JUnit](https://github.com/junit-team/junit4) : a programmer-oriented testing framework for Java.
- [Mockito](https://github.com/mockito/mockito) : a mocking framework for unit tests written in Java.

**Other**

- [MongoDB In-Memory Server](https://github.com/typegoose/mongodb-memory-server) : manage & spin up mongodb server binaries with zero(or slight) configuration for tests.


### Monitoring

- [Grafana](https://github.com/grafana/grafana) : an open-source analytics & monitoring solution for every database.
- [Prometheus](https://github.com/prometheus/prometheus) : an open-source monitoring system with a dimensional data model, flexible query language, efficient time series database and modern alerting approach.
- [Sentry](https://github.com/getsentry/sentry) : a developer-first error tracking and performance monitoring platform.
- [Microsoft Power BI](https://www.microsoft.com/en-us/power-platform/products/power-bi) : a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into coherent, visually immersive, and interactive insights.
- [DataDog](https://www.datadoghq.com/) : a cloud-based monitoring and analytics platform that provides real-time insights into complex IT environments.

### Documentation

- [Doxygen](https://github.com/doxygen/doxygen) : a widely-used and the de facto standard documentation generation tool for C++ (supports other languages).
- [Javadoc](https://en.wikipedia.org/wiki/Javadoc) : an API documentation generator for the Java programming language.
- [Swagger](https://github.com/swagger-api/swagger-ui) : a set of open-source tools for designing, building, documenting, and consuming RESTful APIs.
- [Postman API Documentation tool](https://www.postman.com/api-documentation-tool/) : a tool to generate beautiful, machine-readable documentation for your API and automatically keep it up to date.
- [LaTex](https://www.latex-project.org/) : a typesetting system particularly well-suited for producing technical and scientific documentation.
- [Pandoc](https://github.com/jgm/pandoc) : A universal document converter that can transform files from one markup format into another.

### Devops & CI / CD

**Code Analysis**

- [SonarQube](https://github.com/SonarSource/sonarqube) : a code quality assurance tool that performs in-depth code analysis and generates an analysis report to ensure code reliability.
- [CodeCov](https://about.codecov.io/) : a code analysis tool with which users can group, merge, archive, and compare coverage reports.
- [Resharper by Jetbrains](https://www.jetbrains.com/resharper/) : a powerful software (Visual Studio extension) that offers an intelligent, fast and efficient way to improve your code quality and eliminate errors.


**Workflows & Containerization**

- [Jenkins](https://www.jenkins.io/) : an open-source automation server which enables developers around the world to reliably build, test, and deploy their software.
- [Github Actions](https://github.com/features/actions) : Automate, customize, and execute your software development workflows right in your repository.
- [Act](https://github.com/nektos/act) : a tool to run your GitHub Actions locally 🚀.
- [Portainer](https://github.com/portainer/portainer) : a container management software for Docker, Podman and Kubernetes.
- [Docker](https://www.docker.com/) : a platform designed to help developers build, share, and run container applications 🐳.
- [Kubernetes (k8s)](https://github.com/kubernetes/kubernetes) : an open-source container orchestration system for automating software deployment, scaling, and management.

**IaC (Infrastructure as Code)**

- [Ansible](https://github.com/ansible/ansible) : an open-source IT automation engine that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes.
- [Terraform](https://github.com/hashicorp/terraform) : an infrastructure as code tool that enables you to safely and predictably provision and manage infrastructure in any cloud.
- [Chef](https://github.com/chef/chef) : a powerful automation platform that transforms infrastructure into code automating how infrastructure is configured, deployed and managed across any environment, at any scale.


**Releases**

- [Release Drafter](https://github.com/release-drafter/release-drafter) : Drafts your next release notes as pull requests are merged into master.
- [Semantic Release](https://github.com/semantic-release/semantic-release) : Fully automated version management and package publishing.

**Hosting / Deployment**:

- [NuxtHub](https://hub.nuxt.com/) : a hosting platform specifically designed for Nuxt applications with built-in features like serverless functions and edge caching.
- [Netlify](https://www.netlify.com/) : a cloud computing platform that simplifies the building, deployment, and management of websites.
- [Glitch](glitch.com) : a collaborative online platform that allows users to create, edit, and deploy web applications using Node.js and static web technologies.
- [Vercel](https://vercel.com/) : a cloud platform that enables developers to easily deploy and manage web applications.
- [Heroku](https://www.heroku.com/) : a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.
- [Supabase](https://supabase.com/) : an open-source Firebase alternative.
- [Firebase](https://firebase.google.com/) : a BaaS (Backend As A Service), i.e a bunch of services there to help you build (web) apps.

### Architectures & Design Approaches

- [DDD (Domain Driven Design)](https://www.youtube.com/watch?v=4rhzdZIDX_k) : a major software design approach, focusing on modeling software to match a domain according to input from that domain's experts.
- [TDD (Test Driven Development)](https://circleci.com/blog/test-driven-development-tdd/) : a robust approach that enhances code quality and reliability by ensuring that tests are written before the actual code.
- [Microservices](https://microservices.io/patterns/microservices.html) : an architectural style that structures an application as a collection of two or more services.
- [EDA (Event-Driven Architecture)](https://aws.amazon.com/event-driven-architecture/?nc1=h_ls) : a software architecture paradigm concerning the production and detection of events.

### Other tools

- [GraphQL](https://graphql.org/) : a data query and manipulation language that allows specifying what data is to be retrieved ("declarative data fetching") or modified.
- [Apache Kafka](https://kafka.apache.org/) : a distributed event streaming platform capable of handling high-throughput data feeds.

**Libraries**

- [JsonWebToken (JWT)](https://github.com/auth0/node-jsonwebtoken) : an implementation of JSON Web Tokens, an industry standard for representing claims securely between parties.
- [Socket.io](https://socket.io/) : a library that enables low-latency, bidirectional and event-based communication between web clients and servers.
- [AJV](https://ajv.js.org/) : one of the fastest JSON Schema validators that helps ensure data conforms to specified formats.
- [Zod](https://zod.dev/) : a TypeScript-first schema declaration and validation library designed to be optimized for developer experience.
- [Valibot](https://github.com/fabian-hiller/valibot) : a schema library that validates unknown data and ensures type safety with a tiny bundle size.
- [Stripe](https://github.com/stripe) : a suite of payment APIs that powers commerce for online businesses of all sizes.
- [NextAuth](https://github.com/nextauthjs/next-auth) : a complete open-source authentication solution for Next.js applications.
- [Better Auth](https://github.com/better-auth/better-auth) : a framework-agnostic authentication (and authorization) library for TypeScript
- [Linguist](https://github.com/github-linguist/linguist) : a library created and used by Github to detect blob languages, ignore binary or vendored files, suppress generated files in diffs, and generate language breakdown graphs.

<br><br>
You've reached the end of this awesome list :) ! Don't forget to star ⭐️ !

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details.