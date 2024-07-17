# MERN Authentication Starter

Credits to original source code [github.com/bradtraversy](https://github.com/bradtraversy/mern-auth)
Recoded to be able to using Sequelize & MySQL Database;

### Env Variables

Rename the `.env.example` file to `.env` and add the following

```
NODE_ENV=development
PORT=5000
JWT_SECRET=random_string_123

DB_NAME= your mysql name
DB_USER= your mysql username
DB_PASSWORD= your mysql password
DB_HOST=localhost
```
Change the JWT_SECRET to what you want

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```

# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```