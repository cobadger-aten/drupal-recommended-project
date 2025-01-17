
# Aten Drupal Project

Starting with a standard foundation for all our Drupal projects is a way for us to maintain/manage our sites in a more consistent manner. The packages installed here should be universal throughout our sites at least 90% of the time.

The packages that should be contained in this project are mainly build tools, project-x plugins, etc. Drupal contributed modules will be installed using the `aten/aten-standard` install profile. Which has already been required in the composer.json.

## Get Started

We're using Project-X to help encapsulate redundancy between common project frameworks such as Drupal. The Project-X CLI utility helps speed up local development and standardize the CI workflow to be consistent among multiple hosting platforms, such as Pantheon, Platform.sh, and Acquia.

Most of the platforms might offer their own solutions to these problems, but our goal is to stick to a consistent structure for all of our Aten Drupal projects, so we can easily abide by the Aten Way.

### Drupal 9

```
composer create-project "aten/drupal-recommended-project" [SITE-NAME]
```
