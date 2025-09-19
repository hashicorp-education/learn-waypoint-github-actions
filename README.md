# Example HCP Waypoint GitHub Actions

This repository contains the following GutHub Actions to use as HCP Waypoint Actions:

- [`Clear cache`](./.github/workflows/clear-cache.yml) - Sends an HTTP `PUT` request to a supplied URL with a string value. This is used with the [terraform-aws-terramino-redis](https://github.com/hashicorp-education/terraform-aws-terramino-redis) module to clear the Redis cache.