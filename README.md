# DDEV AdminerEvo

## What is this?

Since Adminer seems not mantained anymore, there is a mantained fork [AdminerEvo](https://github.com/adminerevo/adminerevo). This ddev integration based on the [AdminerEvo Docker Image](https://github.com/shyim/adminerevo-docker) and the original Adminer Addon.

## Installation

* `ddev get aneufeld23/ddev-adminerevo && ddev restart`

Then you can just `ddev adminerevo` or use `ddev describe` to get the URL (`https://<project>.ddev.site:9101`).

## What does this add-on do?

* Adds the AdminerEvo container as a service
