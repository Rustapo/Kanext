# Kanext

> Improved and expanded theme for [kanboard](https://github.com/kanboard/kanboard), that alters both look and functionality.

## Important notice

Version 2.x.x brings fundamental changes to the project, thus please do not update if you are happy previous versions.

## Screenshot

This screenshot is made together with the **GreenWing** plugin/template, which we strongle recommend.

![Dashboard with GreenWing and Kanext](/.screenshots/dashboard.png?raw=true "Dashboard with GreenWing and Kanext")

## Kanboard

Kanboard provides the basic necessary functionality for handling kanban projects. Moreover, it is a popular piece of software with a lot of community support.
Kanboard is currently at **1.2.11**.

## Kanext theme

`Kanext` is short for `Kanboard-Extended` :) . This plugin is supposed to change some parts of the templates kanboard uses (e.g. the dashboard) to increase productivity for small teams.

Other UI improvements are available as well:

- different menu structure;
- just another CSS theme;
- small changes in the overall functionality (e.g. close modal on outside click, close dropdown on second click in the anchor)

## Development

- path assumptions:
  - `@/` is the root of `Kanboard`;
  - `~/` is the root of this repo;
  - `./` is an alias of `~/src`.
- the source code for the theme is in `~/src`;
- `~/Plugin.php` a placeholder which only loads the main plugin file, in case the the install was done by cloning the repo.
- `Docker` / `docker-compose` required (these commands are assumed in `./.docker/`):
  - ! Important notice ! This is a development only option;
  - start command: `docker-compose up --build --force-recreate` or `docker-compose start`;
    - `kanboard` will be available at [http://localhost:88](http://localhost:88)
  - stop: `docker-compose stop`
