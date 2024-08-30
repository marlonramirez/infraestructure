# Configuration

* clone

```
git clone git@github.com:sespesoft/auth.git
```

```
git clone git@github.com:sespesoft/pqrs.git
```

```
git clone git@github.com:sespesoft/pgaudit-api.git
```

```
git clone git@github.com:sespesoft/webapp.git -b auth
```

```
git clone git@github.com:sespesoft/audit.git -b authentication-service
```

rename files `example.dev` to `env`.

* execute

```
docker compose up -d
docker compose rm -f
```

# assets
This repository management assets of sespesoft customers

In order to change the additional context you must do this:
```
assets=https://github.com/marlonramirez/infraestructure.git#:_assets/caresoft-dev
```
