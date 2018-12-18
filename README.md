# Adonis fullstack application

This is the fullstack boilerplate for AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Session
3. Authentication
4. Web security middleware
5. CORS
6. Edge template engine
7. Lucid ORM
8. Migrations and seeds

## Setup

Clone repository with

```bash
git clone http://github.com/setiawan1998/netflix_backend.git
```

or manually downloaded the zip file, then

```bash
npm install
```


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
adonis key:generate
```

### Environment
Setup the following setting in `.env` file

```bash
HOST=your_host
PORT=your_port
DB_CONNECTION=your_db
DB_HOST=your_db_host
DB_PORT=your_db_port
DB_USER=your_db_username
DB_PASSWORD=your_db_password
DB_DATABASE=your_db_database

```
