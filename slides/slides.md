## Assumptions

----

### You have a data app

Any one of the following:

- Flask
- Streamlit
- Panel
- other?

----


![GitHub logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

- Make sure you have an account
- You should know basics:
  - Pushing
  - Pulling
  - Committing Files

----


![Anaconda logo](https://www.pinclipart.com/picdir/big/180-1800785_anaconda-python-logo-clipart.png)

Make sure it's installed on your computer!

----


![Heroku logo](https://seekvectorlogo.net/wp-content/uploads/2018/12/heroku-vector-logo.png)

Sign up for a free account.

---

## Review

----

### `git`-based workflow

- App in `git` repository.
- Automatic deploys from `master`.

----

### `conda` environments

- Reproducible development environment.
- Example environment file.

```yaml
name: demo-streamlit-heroku
channels:
- conda-forge
dependencies:
- python=3.8
- conda
- pandas
# put more stuff below
```

----

### Config-file-based infrastructure

- `requirements.txt`: Python project dependencies.
- `Procfile`: Runtime environment declaration.
- `environemnt.yml`: Development environment.

----

### Platform as a Service (PaaS)

- No manual configuration of web servers!

- If you've wrestled with web servers before,
this is a breath of fresh air.

- If you've never wrestled with web servers before,
I hope you never have to!


----

### Things not covered

1. Complex apps
1. Pulling in pre-trained models
1. Pulling in from container registry

Let me know if these interest you!

---

## Your Project!

1. Deploy your app to Heroku.
1. Share it with the world.
1. Tweet it to me (`@ericmjl`).

Leave questions on Skillshare!
