## Django middleware for cassette.dev

Add `django-cassette` to your installed apps.

```
INSTALLED_APPS = [
    ...
    'django-cassette',
    ...
]
```

Add the middleware as at the end of the middleware list

```
MIDDLEWARE = [
    ...
    'django_cassette.middleware.CassetteMiddleware,
]
```

Now you're good to go! To import your API just install cassette's cli (`npm install -g @cassette.dev/cli`)
and follow the instructions.