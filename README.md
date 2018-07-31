# EditVR Project

This repository is used to create an EditVR project featuring Contenta CMS using Composer.

```
# Create the project in your local environment.
composer create-project editvr/editvr-project editvr --stability dev --no-interaction

# Install Drupal.
cd editvr/web
drush si contenta_jsonapi \
  --db-url=mysql://db-user:db-password@localhost/db-name \
  --site-mail=admin@localhost \
  --site-name='EditVR' \
  --account-mail=admin@localhost \
  --account-name=admin \
  --account-pass=admin -y
```

If you want documentation about Contenta CMS visit http://www.contentacms.org.