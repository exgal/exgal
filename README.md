<h1 align="center">The ExGal Community🚀</h1>
<h6 align="center">The liberal community of all Star Wars fans</h6>

<p align="center">
    <img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/exgal/exgal/PHP%20CI%20&%20Test?label=Github%20Actions%20CI&logo=github&style=flat-square">
    <img alt="GitHub" src="https://img.shields.io/github/license/exgal/exgal?style=flat-square">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/exgal/exgal?logo=github&style=flat-square">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/exgal/exgal?style=flat-square">
    <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/exgal/exgal?logo=eye&style=flat-square">
</p>

## About The ExGal

### In Star Wars

> The **Extragalactic Society** (often referred to as simply **ExGal**) was an organization devoted to the search for life outside [the galaxy](https://starwars.fandom.com/wiki/The_galaxy/Legends).[[1\]](https://starwars.fandom.com/wiki/Extragalactic_Society#cite_note-VP-1) During the time of the [Galactic Republic](https://starwars.fandom.com/wiki/Galactic_Republic/Legends), it was a member of the [General Ministry Institutes](https://starwars.fandom.com/wiki/General_Ministry_Institutes).[[2\]](https://starwars.fandom.com/wiki/Extragalactic_Society#cite_note-HNN-2)

--- from Wookieepedia

### About The Project🌏

The ExGal  website is the forum of Star Wars fans written in PHP 8.0 and Laravel😊

This repo is the backend api of the website

### The Tech Stack of the ExGal⚒

[![](https://img.shields.io/badge/-Linux-f2c63f?style=flat-square&logo=linux&logoColor=ffffff)](https://kernel.org/)
[![](https://img.shields.io/badge/-PHP-8892bf?style=flat-square&logo=php&logoColor=ffffff)](https://php.net/)
[![](https://img.shields.io/badge/-Laravel-ff2d20?style=flat-square&logo=laravel&logoColor=ffffff)](https://php.net/)
[![](https://img.shields.io/badge/-Docker-0167fe?style=flat-square&logo=docker&logoColor=ffffff)](https://www.docker.com/)
[![](https://img.shields.io/badge/-Apache-f00?style=flat-square&logo=apache&logoColor=ffffff)](https://www.apache.org/) 
[![](https://img.shields.io/badge/-PostgreSQL-346891?style=flat-square&logo=postgresql&logoColor=ffffff)](https://www.postgresql.org/)
[![](https://img.shields.io/badge/-Redis-a51f17?style=flat-square&logo=redis&logoColor=ffffff)](https://www.redis.com/)

## Installation  & Setting up dev environment🍺

The guide for installing the application

### Requirements

If you want to run this application, you will need

#### Running Environment

- [x] **PHP 8.0** for the php runtime
- [x] **Composer** as the package manager
- [x] **Docker** as the container for _Laravel Sail_
- [x] **docker-compose** to manage services & containers in docker

#### Other Services

- [x] **An [_Authing.co_](https://authing.co) account & a userpool** for authentication & authorization in development
- [x] **An _[Onesignal](https://onesignal.com/)_ account** for message pushing in development

That's all

**You should fork the repo if you want to contribute to it !!**

### Clone the project

if you want have forked the repo

```shell
git clone git@github.com:{YOUR_USERNAME}/exgal.git
```

or you just want to read the code 

```shell
git clone git@github.com:exgal/exgal.git
```

### Install dependencies

Install the dependencies with composer 🎼

```shell
composer install
```

### Copy env file

copy the `.env.example` to `.env` 

```shell
cp .env.example .env
```

### Generate Key🔑

Generate the key

```shell
php artisan key:generate
```

### Config the env file

You can change the configuration in the  `.env` file according to your own condition

### Setup Laravel Sail environment⚓

the ExGal project api runs on a laravel sail environment (with Docker) in developement

run the following command to setup the sail environment

```shell
./vendor/bin/sail up -d
```

### Migrate database

make database migration

```shell
php artisan migrate --seed
```

**Wow, you made it !! 🚀**

For information about contributing, see the part [#Contributing💗](#Contributing💗)

## Table of the Packages used 📦

These are the packages used in the ExGal website api project

### In Production

| Package📦                           | description                                  | usage                                            |
| ---------------------------------- | -------------------------------------------- | ------------------------------------------------ |
| authing-sdk/php                    | the SDK of Authing.co for PHP                | use authing.co for authentication&authorization  |
| awssat/laravel-visits              | counting the visits of an entity             | for counting the visits of pages and articles    |
| berkayk/onesignal-laravel          | the OneSignal SDK for Laravel                | for pushing notifications with OneSignal         |
| guzzlehttp/guzzle                  | HTTP request package                         | making http request to other online services     |
| laravel/scout                      | full-text searching                          | full-text searching of articles with MeiliSearch |
| mll-lab/laravel-graphql-playground | Graphql testing                              | graphql api testing (disabled in production)     |
| nuwave/lighthouse                  | a framework for serving GraphQL from Laravel | serving GraphQL APIs                             |

### In Dev

| Package📦        | description                         | usage                                  |
| --------------- | ----------------------------------- | -------------------------------------- |
| laravel/sail    | Laravel dev environment with docker | building local development environment |
| phpunit/phpunit | PHP Unit testing tool               | doing PHP Unit testing                 |

## Docs 📖

Coming soon

## Contributing💗

Thank you for considering contributing to the ExGal! The contribution guide is coming soon

## Code of Conduct📚

Coming Soon

## License📘

The ExGal project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
