{{cookiecutter.name}}
---------------------

This is the salt primer layout for your salt project it consists of:


```
{{cookiecutter.name}}
├── .gitignore
├── formulas
├── pillars
│   └── tops.sls
└── profiles
   └── tops.sl
```

## formulas

These are the salt formulas you want to use in your project

```
primer add formulas git://...
```


## pillars

These are the secret pillar settings for applications and their host mapping (tops.sls)

```

```


## profiles

These are the state settings for applications in your system (nginx, rabbitmq, etc) and their host mapping (tops.sls)

```

```