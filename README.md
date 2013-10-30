keybits-server
==============

**Ansible playbooks and Dockerfiles to help you set up a personal server.**

### WARNING

This is a **'Work in Progress'**. Things are likely to change and be broken.

Please install on a test server and report issues to help us improve these playbooks and associated docker images.

**Do not trust your critical data to a server installed using this system until further notice.**

## Project website

Please see the main project website <http://keybits.net> for background.

## Documentation

For step-by-step instructions please [read the docs](http://docs.keybits.net)

## Email newsletter

Keep update by subscribing to the newsletter on the project website <http://keybits.net>

## Current functionality

If you follow the documentation and run the playbook here you will get:

- Secured server
- Landing page
- Ghost blog
- Piwik analytics

You will be able to update these apps and add new apps as we develop the playbook simply by pulling an updated version of this repository and then running the playbook again.

## Roadmap

See [roadmap](http://docs.keybits.net/en/latest/todo.html#roadmap)

## Known problems

- Docker containers don't always start on first run of the playbooks - we are looking into this
- Docker containers are built on the server - this is slow and inefficient - they'll be published to the registry when better optimised.
- Some permissions issues need sorting so that you can easily edit files and update the default landing page
- The documentation is somewhat incomplete with regard to what to do when the server is up and running - this will be coming very soon!
- No backups! Currently we do not show how to back up your data