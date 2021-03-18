Steps:

- Use the command `code ~/.bashrc` to open your bashrc file
- Comment out the PGUSER and PGPASSWORD lines
- Clone this repo
- Enter into the psql shell with `psql`
- User the command `CREATE USER permission_fix_user WITH CREATEDB;`
- Exit the psql shell with `\q`
- While inside the project, use `npm install`
- Finally use `npx sequelize db:create`

Hopefully that works! Otherwise we'll keep troubleshooting.