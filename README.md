# prisma-demo1

```bash
npm install
```


create an empty database
```sql
CREATE DATABASE database4;
```

update the .env file with your own connection string - for example:
```env
DATABASE_URL="mysql://root:123456@localhost:3306/database4"
```

create migration files
```bash
npx prisma migrate dev
```

run the app
```bash
npm start
```

This will run the script from package.json:
```json
  "scripts": {
    "start": "npx prisma generate && node index.js"
```

