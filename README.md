# bespoke-blog
Design and Implementation of my own blog website

## Design
* Next.js for front-end. Chosen mainly for it's server side rendering which will help SEO later. Also supports typescript which will be used.

* Rust for the back-end. Will use Actix Web due to previous positive experience in university Junior Honours project.

* Postgres as the database, from experience has more features than Mariadb and less problems. Also chosen as a learning experience of a different database.

* Docker used to help faciliate development on multiple machines and later on for deployment.

## Development

Using cargo-watch and the next.js development server, it is possible to run both docker containers and have real-time updating / recompiling / testing upon writing new code. Without having to rebuild either docker image, saving time whilst also being a nice QoL change.
