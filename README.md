![Logo Filecify](https://i.imgur.com/CHwnhsO.png)

[![MADE BY Django](https://img.shields.io/badge/Made%20with%20Django-000000.svg?style=flat&logo=Django&labelColor=000)](https://www.djangoproject.com/)

Project gemaakt voor het vak K-sec op het Mediacollege

Applicatie om video's te uploaden op de meest veilige manier mogelijk. Wanneer het project word gecloned is het ook mogelijk
om onder andere video's te verwijderen of aan te passen via het admin paneel.

Project gemaakt met Python framework Django in Visual Studio Code met de laatste versie van beide Python (3.9.0) en Django (3.1.2). Info hierover is te zien in [Google docs](https://docs.google.com/document/d/1X3cLMAq5acO5IeP4wIgmPsOeRnepxQgw45YJ14Dy_X0/edit?usp=sharing).

## Demo

Na de [installatie](https://docs.djangoproject.com/en/3.1/intro/install/) van Python en Django is het project gelijk te gebruiken, lees hieronder hoe je dat doet.

- Clone het project via: Code > Download ZIP
- Unzip het project en open het in je favoriete text editor, een IDE is niet nodig
- Klik op het adres in file explorer en type 'cmd'. Zet daarna de lijn code hieronder in de command prompt

```
 $  py manage.py runserver
```

## Features

- **Cross site scripting (XSS) protection**: XSS attacks allow a user to inject client side scripts into the browsers of other users.
- **Cross site request forgery (CSRF) protection**: CSRF attacks allow a malicious user to execute actions using the credentials of another user without that user’s knowledge.
- **SQL injection protection**: SQL injection is a type of attack where a malicious user is able to execute arbitrary SQL code on a database.
- **Clickjacking protection**: Clickjacking is a type of attack where a malicious site wraps another site in a frame.
- **SSL/HTTPS**: It is always better for security to deploy your site behind HTTPS.
- **Host header validation**: Django uses the Host header provided by the client to construct URLs in certain cases.
- **Referrer policy**: Browsers use the Referer header as a way to send information to a site about how users got there.
- **Session security**: Similar to the CSRF limitations requiring a site to be deployed such that untrusted users don’t have access to any subdomains.

## Dependencies

- [TypeScript](https://www.typescriptlang.org/)
- [Django](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)

## Structure

Hieronder is de structuur van het project te zien. 

```
filecify/
     manage.py
     db.sqlite3
      app/
         ├── admin.py
         ├── apps.py
         ├── forms.py
         ├── models.py
         └── tests.py
         └── validators.py
         └── views.py
      project/
         ├── init.py
         ├── settings.py
         ├── urls.py
         ├── asgi.py
         └── wsgi.py
```

## References

- [Django](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)
- [Google docs](https://docs.google.com/document/d/1X3cLMAq5acO5IeP4wIgmPsOeRnepxQgw45YJ14Dy_X0/edit?usp=sharing)
- [Design](https://www.figma.com/file/2X0vmmz2YwuwHLaQk3SGQh/Filecify?node-id=0%3A1)

## License

MIT
