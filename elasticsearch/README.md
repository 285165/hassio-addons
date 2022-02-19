# Home assistant add-on: elasticsearch server

[![Donate][donation-badge]](https://www.buymeacoffee.com/alexbelgium)

[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=flat&logoColor=white

![Supports
 Architecture][aarch64-shield] ![Supports amd64 Architecture][amd64-shield]

_Thanks to everyone having starred my repo! To star it click on the image below, then it will be on top right. Thanks!_

[![Stargazers repo roster for @alexbelgium/hassio-addons](https://reporoster.com/stars/alexbelgium/hassio-addons)](https://github.com/alexbelgium/hassio-addons/stargazers)

## About

---

[Elasticsearch](https://github.com/elastic/elasticsearch) is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/fr/products/).
You can use Elasticsearch to store, search, and manage data for:

- Logs
- Metrics
- A search backend
- Application monitoring
- Endpoint security
- ... and more!

To learn more about Elasticsearch’s features and capabilities, see their [product page](https://www.elastic.co/fr/elasticsearch/) .

Here, this addon is used to single node that can be called from other addons needing it.

## Installation

---

The installation of this add-on is pretty straightforward and not different in comparison to installing any other add-on.

1. Add my add-ons repository to your home assistant instance (in supervisor addons store at top right, or click button below if you have configured my HA) [![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Falexbelgium%2Fhassio-addons)
2. Install this add-on.
3. Click the `Save` button to store your configuration.
4. Set the add-on options to your preferences
5. Start the add-on.
6. Check the logs of the add-on to see if everything went well.

## Configuration

No webui, no addon options.
Elasticsearch is using by calling it from another app, such as nextcloud.

## Integration with HA

Component : https://community.home-assistant.io/t/elasticsearch-component-publish-home-assistant-events-to-elasticsearch/66877

## Support

Create an issue on github

[ssl-shield]: https://img.shields.io/badge/ssl-yes-green.svg
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
