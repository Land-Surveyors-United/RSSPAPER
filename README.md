<h1 align="center">
  <img alt="RSSpaper logo" src="logo.png">
</h1>
<p align="center">
  <a href="https://rsspaper.andros.dev/">👉 DEMO 👈</a>
</p>

## Run

1) Make sure you have Java installed.

Debian/Ubuntu

``` sh
sudo apt install default-jre
```

Mac OS

``` sh
brew install java
```

2) Create a file `config.yaml` with the following content. You can also use `config.yaml.example` as a base config and change it to fit your needs.

``` yaml
title: RSSPaper

# Options: light or dark
theme: light

# Options: daily, weekly or all
edition: weekly

feeds:
  - https://programadorwebvalencia.com/feed/
  - https://republicaweb.es/feed/
```

3) Download the latest version of RSSpaper (`rsspaper-{version}-standalone.jar`).

https://github.com/tanrax/RSSpaper/releases


4) Now you can execute glosa.

```sh
java -jar rsspaper-{version}-standalone.jar
```

Great 🎉. You already have your 🔥 own Static RSS Newspaper 🔥.

That's it, now you just have to open `dist/index.html`.

## Testing

``` sh
lein check-idiomatic
lein check-format
```
