# librdkafka buildpack

This buildpack compiles librdkafka for use with [node-rdkafka](https://github.com/Blizzard/node-rdkafka).

## Usage

  * This buildpack expects that you have at least the heroku standard nodejs buildpack. This buildpack should come first so that librdkafka gets installed before `yarn install node-rdkafka` gets run.
  * Set up like so:
  ```
  heroku buildpacks:set https://github.com/SalesforceCloudServices/heroku-buildpack-librdkafka-1.0.git
  ```

