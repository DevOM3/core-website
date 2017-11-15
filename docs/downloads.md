# Downloads

## Docker Images

Frontira consists of a core set of services, including QIX Engine, that can be downloaded as Docker images:

| Service    | Feature | Docker Image | Source Code |
| ---------- | ------- | ------------ | ----------- |
| [QIX Engine](./docs/services/qix-engine/) | The powerful associative indexing engine from Qlik and the foundation of Frontira | [qlikea/engine](https://hub.docker.com/r/qlikea/engine) | Closed source |
| [License Service](./docs/services/license-service/) | Service required to run QIX Engine with a valid license | [qlikea/license-service](https://hub.docker.com/r/qlikea/license-service) | Closed source |
| [Mira](./docs/services/mira/) | QIX Engine discovery service | [qlikea/mira](https://hub.docker.com/r/qlikea/mira) | [GitHub](https://github.com/qlik-ea/mira) |

## JavaScript Libraries

Several open source JavaScript libraries exist that are useful when working with Frontira. These can be installed as
npm packages:

| Library | Feature | Source Code |
| ------- | ------- | ----------- |
| [enigma.js](https://www.npmjs.com/package/enigma.js) | Communication with the QIX Engine | [GitHub](https://github.com/qlik-oss/enigma.js/) |
| [halyard.js](https://www.npmjs.com/package/halyard.js) | Simplifies data loading into the QIX Engine | [GitHub](https://github.com/qlik-oss/halyard.js) |
| [after-work.js](https://www.npmjs.com/package/after-work.js) | Unified testing framework for different test levels | [GitHub](https://github.com/qlik-oss/after-work.js) |
| picasso.js | Visualization library on top of the QIX Engine | Not released yet |