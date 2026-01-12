# Local WordPress Environment Walkthrough

Your local WordPress site is now set up and running with Docker!

## Accessing Your Site
- **Website**: [http://localhost:8000](http://localhost:8000)
- **Admin Panel**: [http://localhost:8000/wp-admin](http://localhost:8000/wp-admin)
    - Use your existing credentials (from the imported database).
- **Database Manager (phpMyAdmin)**: [http://localhost:8080](http://localhost:8080)

## Managing the Server

### Starting the Server
To start the site next time, open your terminal in the project folder and run:
```bash
docker-compose up -d
```

### Stopping the Server
To stop the site and free up resources:
```bash
docker-compose down
```

### Checking Logs
If something goes wrong, you can check the logs:
```bash
docker-compose logs -f
```

## Important Notes
- **Database**: Your database was automatically imported from `u640336053_UB95s.sql`. Changes you make locally (new posts, settings) are saved in the `db_data` folder and NOT in the SQL file.
- **Git**: Remember to commit your `wp-content/themes` changes, but ignore the core WordPress files.
