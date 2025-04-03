_2025-April-03 -- archiving this repo. It was for an experiment that wasn't pursued._

# purpose

This is a lightweight -- no database -- django webapp to be a testbed / development-bed for the public version of the Stolen-Relations public website.

_(Note: I removed a few things from the default db-install that are still in the [project_copy_with_db_support](https://github.com/birkin/sr_public_webapp_project/tree/project_copy_with_db_support) branch -- that I can easily put back if desired. (ie if there's a desire to use django's build-in admin and/or authentication system.))_

The sample-urls implement a request for a few ways to load and display json content.


# local-install

(assumes docker is installed)

```
$ mdir ./sr_public_webapp_stuff
$ cd ./sr_public_webapp_stuff/
$ git clone git@github.com:Brown-University-Library/sr_public_webapp_project.git
$ cd ./sr_public_webapp_project/
$ docker-compose up
```

Then open a browser to <http://127.0.0.1:8000/sample_index/> for sample urls.

---
