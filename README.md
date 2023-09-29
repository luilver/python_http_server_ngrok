# Python HTTP server with ngrok

An easy way to share your local files quickly

![Running service][]

## Setup

Run the following command:
```
$ ./bin/setup
```

## Configs

Edit your local files `.env` and `ngrok/ngrok.yml`

### Dot ENV file

Replace `/path/to/local/folder/to/be/shared` with your desired filesystem folder
to be shared. Ex: `/home/luilver/bin` will share all my scripts # As previously
shown ( :

### Nogrok YAML file

Replace your_auth_token_here with your ngrok auth token

Don't forget to save your files before continue

## Run

```
$ docker-compose up -d
```

Voilà!

## Motivation

There is no a simple integration like this under [nogrok site][]. Hopefully this
would help someone else that, just like me, wanted to share some files with a
group of friends.

Thanks to informín.

  [nogrok site]: https://ngrok.com/docs/integrations/
  [Running service]: images/service_running.png
