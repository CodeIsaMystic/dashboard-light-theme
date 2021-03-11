<div align="center">
<h1> DASHBOARD LIGHT THEME APPLICATION </h1>

<a href="#">
  <img
    height="60"
    width="240"
    alt="dbsh-logo"
    src="app/assets/img/icons/logo-dbsh--light.svg"
  />
</a>

<p>Intro explaining the purpose of this project,  and how it can envolve with time... </p>

<br />

<a href="#">
  <img
    height=""
    width=""
    alt="screen of dashboard ligth theme project"
    src="app/assets/img/"
  />
</a>

<br />
</div>




# Getting Started

This app is a basic backend dashboard for simple projects. [Dashboard-light-theme](https://github.com/CodeIsaMystic/dashboard-light-theme) have some basics and standards applications, you can imagine so, handling texts, SEO, Titles, Cards, Images, Users, Contacts, Lists, Articles, Posts and so on...
You can of course implementing more applications on it like charts with Chart.js.

## SQL Database

I used it on project with SQL Database and PHP backend. SQL databases are a powerful, open source object-relational database system that uses and extends the `SQL` language combined with many features that safely store and scale the most complicated data workloads. Create a database to store two tables.

### Create Database

`CREATE DATABASE` creates a new SQL database.

```sql
CREATE DATABASE "your-database-name";
```

### Create Tables

To create a new table, you use the `CREATE TABLE` statement. Make sure to create the tables in the `face-model-storage` database.

```sql
CREATE TABLE "your-database-name-and-table-name-here" (
  id VARCHAR(36) NOT NULL PRIMARY KEY,
  first_name TEXT NOT NULL,
  last_name TEXT NOT NULL,
  email TEXT NOT NULL UNIQUE,
  password TEXT NOT NULL,
  entries INTEGER NOT NULL DEFAULT 0
);
```

Explain here what's stored in `your-database-name-and-table-name-too` and then what's stored in  `other-table-name` too.

```sql
CREATE TABLE "other-table-name" (
  serial SERIAL NOT NULL PRIMARY KEY,
  timestamp TIMESTAMP NOT NULL,
  id VARCHAR(36) NOT NULL,
  email TEXT NOT NULL,
  image TEXT NOT NULL
);
```

## Environment Variables


## Developing

Fork the repository using [this](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) guide, then clone it locally.

```shell
git clone https://github.com/CodeIsaMystic/dashboard-light-theme
cd your-name-folder
npm install
```

You can run the app on dev mode.

```shell
npm run dev
```

## License

```text
here License
&
Copyright (c) 2021
```