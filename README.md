# Start Wordpress

```bash
docker-compose up
./scripts/startup
```

# Scripts

- `scripts/wp`: use the WordPress CLI
- `scripts/{import,export}-data`: import/export the MySQL database (WP settings, data, etc.)

# Other stuff

- WP API is at `http://localhost:8080/wp-json/wp/v2/`
- username/passwd is wpress/wpress
