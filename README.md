> Just make a `.env` file and change configs if you want:

```bash
cp .env.example .env
```

```bash
docker compose up -d
```

Then open the `phpmyadmin` in whatever port you set in `PMA_PORT`.

the default is `8080`