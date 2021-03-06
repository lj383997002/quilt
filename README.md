[comment]: # (NOTE: This file is generated and should not be modify directly. Update `templates/ROOT_README.hbs.md` instead)
# quilt

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.md)
[![Build Status](https://travis-ci.org/Shopify/quilt.svg?branch=master)](https://travis-ci.org/Shopify/quilt)
[![codecov](https://codecov.io/gh/Shopify/quilt/branch/master/graph/badge.svg)](https://codecov.io/gh/Shopify/quilt)
[![Greenkeeper badge](https://badges.greenkeeper.io/Shopify/quilt.svg)](https://greenkeeper.io/)
[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)

A loosely related set of packages for JavaScript / TypeScript projects at Shopify.

These libraries compose together to help you create performant modern JS apps that you love to develop and test. These packages are developed primarily to be used on top of the stack we like best for our JS apps; Typescript for the flavor, Koa for the server, React for UI, Apollo for data fetching, and Jest for tests. That said, you can mix and match as you like.

## Usage

The Quilt repo is managed as a monorepo that is composed of many npm packages.
Each package has its own `README` and documentation describing usage.

### Package Index

| package |     |     |
| ------- | --- | --- |
| address | [directory](packages/address) | [![npm version](https://badge.fury.io/js/%40shopify%2Faddress.svg)](https://badge.fury.io/js/%40shopify%2Faddress) |
| address-consts | [directory](packages/address-consts) | [![npm version](https://badge.fury.io/js/%40shopify%2Faddress-consts.svg)](https://badge.fury.io/js/%40shopify%2Faddress-consts) |
| address-mocks | [directory](packages/address-mocks) | [![npm version](https://badge.fury.io/js/%40shopify%2Faddress-mocks.svg)](https://badge.fury.io/js/%40shopify%2Faddress-mocks) |
| admin-graphql-api-utilities | [directory](packages/admin-graphql-api-utilities) | [![npm version](https://badge.fury.io/js/%40shopify%2Fadmin-graphql-api-utilities.svg)](https://badge.fury.io/js/%40shopify%2Fadmin-graphql-api-utilities) |
| ast-utilities | [directory](packages/ast-utilities) | [![npm version](https://badge.fury.io/js/%40shopify%2Fast-utilities.svg)](https://badge.fury.io/js/%40shopify%2Fast-utilities) |
| async | [directory](packages/async) | [![npm version](https://badge.fury.io/js/%40shopify%2Fasync.svg)](https://badge.fury.io/js/%40shopify%2Fasync) |
| csrf-token-fetcher | [directory](packages/csrf-token-fetcher) | [![npm version](https://badge.fury.io/js/%40shopify%2Fcsrf-token-fetcher.svg)](https://badge.fury.io/js/%40shopify%2Fcsrf-token-fetcher) |
| css-utilities | [directory](packages/css-utilities) | [![npm version](https://badge.fury.io/js/%40shopify%2Fcss-utilities.svg)](https://badge.fury.io/js/%40shopify%2Fcss-utilities) |
| dates | [directory](packages/dates) | [![npm version](https://badge.fury.io/js/%40shopify%2Fdates.svg)](https://badge.fury.io/js/%40shopify%2Fdates) |
| decorators | [directory](packages/decorators) | [![npm version](https://badge.fury.io/js/%40shopify%2Fdecorators.svg)](https://badge.fury.io/js/%40shopify%2Fdecorators) |
| enzyme-utilities | [directory](packages/enzyme-utilities) | [![npm version](https://badge.fury.io/js/%40shopify%2Fenzyme-utilities.svg)](https://badge.fury.io/js/%40shopify%2Fenzyme-utilities) |
| function-enhancers | [directory](packages/function-enhancers) | [![npm version](https://badge.fury.io/js/%40shopify%2Ffunction-enhancers.svg)](https://badge.fury.io/js/%40shopify%2Ffunction-enhancers) |
| graphql-persisted | [directory](packages/graphql-persisted) | [![npm version](https://badge.fury.io/js/%40shopify%2Fgraphql-persisted.svg)](https://badge.fury.io/js/%40shopify%2Fgraphql-persisted) |
| graphql-testing | [directory](packages/graphql-testing) | [![npm version](https://badge.fury.io/js/%40shopify%2Fgraphql-testing.svg)](https://badge.fury.io/js/%40shopify%2Fgraphql-testing) |
| i18n | [directory](packages/i18n) | [![npm version](https://badge.fury.io/js/%40shopify%2Fi18n.svg)](https://badge.fury.io/js/%40shopify%2Fi18n) |
| jest-dom-mocks | [directory](packages/jest-dom-mocks) | [![npm version](https://badge.fury.io/js/%40shopify%2Fjest-dom-mocks.svg)](https://badge.fury.io/js/%40shopify%2Fjest-dom-mocks) |
| jest-koa-mocks | [directory](packages/jest-koa-mocks) | [![npm version](https://badge.fury.io/js/%40shopify%2Fjest-koa-mocks.svg)](https://badge.fury.io/js/%40shopify%2Fjest-koa-mocks) |
| jest-mock-apollo | [directory](packages/jest-mock-apollo) | [![npm version](https://badge.fury.io/js/%40shopify%2Fjest-mock-apollo.svg)](https://badge.fury.io/js/%40shopify%2Fjest-mock-apollo) |
| jest-mock-router | [directory](packages/jest-mock-router) | [![npm version](https://badge.fury.io/js/%40shopify%2Fjest-mock-router.svg)](https://badge.fury.io/js/%40shopify%2Fjest-mock-router) |
| koa-liveness-ping | [directory](packages/koa-liveness-ping) | [![npm version](https://badge.fury.io/js/%40shopify%2Fkoa-liveness-ping.svg)](https://badge.fury.io/js/%40shopify%2Fkoa-liveness-ping) |
| koa-metrics | [directory](packages/koa-metrics) | [![npm version](https://badge.fury.io/js/%40shopify%2Fkoa-metrics.svg)](https://badge.fury.io/js/%40shopify%2Fkoa-metrics) |
| koa-performance | [directory](packages/koa-performance) | [![npm version](https://badge.fury.io/js/%40shopify%2Fkoa-performance.svg)](https://badge.fury.io/js/%40shopify%2Fkoa-performance) |
| koa-shopify-auth | [directory](packages/koa-shopify-auth) | [![npm version](https://badge.fury.io/js/%40shopify%2Fkoa-shopify-auth.svg)](https://badge.fury.io/js/%40shopify%2Fkoa-shopify-auth) |
| koa-shopify-graphql-proxy | [directory](packages/koa-shopify-graphql-proxy) | [![npm version](https://badge.fury.io/js/%40shopify%2Fkoa-shopify-graphql-proxy.svg)](https://badge.fury.io/js/%40shopify%2Fkoa-shopify-graphql-proxy) |
| koa-shopify-webhooks | [directory](packages/koa-shopify-webhooks) | [![npm version](https://badge.fury.io/js/%40shopify%2Fkoa-shopify-webhooks.svg)](https://badge.fury.io/js/%40shopify%2Fkoa-shopify-webhooks) |
| logger | [directory](packages/logger) | [![npm version](https://badge.fury.io/js/%40shopify%2Flogger.svg)](https://badge.fury.io/js/%40shopify%2Flogger) |
| network | [directory](packages/network) | [![npm version](https://badge.fury.io/js/%40shopify%2Fnetwork.svg)](https://badge.fury.io/js/%40shopify%2Fnetwork) |
| performance | [directory](packages/performance) | [![npm version](https://badge.fury.io/js/%40shopify%2Fperformance.svg)](https://badge.fury.io/js/%40shopify%2Fperformance) |
| polyfills | [directory](packages/polyfills) | [![npm version](https://badge.fury.io/js/%40shopify%2Fpolyfills.svg)](https://badge.fury.io/js/%40shopify%2Fpolyfills) |
| predicates | [directory](packages/predicates) | [![npm version](https://badge.fury.io/js/%40shopify%2Fpredicates.svg)](https://badge.fury.io/js/%40shopify%2Fpredicates) |
| react-app-bridge-universal-provider | [directory](packages/react-app-bridge-universal-provider) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-app-bridge-universal-provider.svg)](https://badge.fury.io/js/%40shopify%2Freact-app-bridge-universal-provider) |
| react-async | [directory](packages/react-async) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-async.svg)](https://badge.fury.io/js/%40shopify%2Freact-async) |
| react-compose | [directory](packages/react-compose) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-compose.svg)](https://badge.fury.io/js/%40shopify%2Freact-compose) |
| react-cookie | [directory](packages/react-cookie) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-cookie.svg)](https://badge.fury.io/js/%40shopify%2Freact-cookie) |
| react-csrf | [directory](packages/react-csrf) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-csrf.svg)](https://badge.fury.io/js/%40shopify%2Freact-csrf) |
| react-csrf-universal-provider | [directory](packages/react-csrf-universal-provider) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-csrf-universal-provider.svg)](https://badge.fury.io/js/%40shopify%2Freact-csrf-universal-provider) |
| react-effect | [directory](packages/react-effect) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-effect.svg)](https://badge.fury.io/js/%40shopify%2Freact-effect) |
| react-form | [directory](packages/react-form) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-form.svg)](https://badge.fury.io/js/%40shopify%2Freact-form) |
| react-form-state | [directory](packages/react-form-state) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-form-state.svg)](https://badge.fury.io/js/%40shopify%2Freact-form-state) |
| react-google-analytics | [directory](packages/react-google-analytics) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-google-analytics.svg)](https://badge.fury.io/js/%40shopify%2Freact-google-analytics) |
| react-graphql | [directory](packages/react-graphql) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-graphql.svg)](https://badge.fury.io/js/%40shopify%2Freact-graphql) |
| react-graphql-universal-provider | [directory](packages/react-graphql-universal-provider) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-graphql-universal-provider.svg)](https://badge.fury.io/js/%40shopify%2Freact-graphql-universal-provider) |
| react-hooks | [directory](packages/react-hooks) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-hooks.svg)](https://badge.fury.io/js/%40shopify%2Freact-hooks) |
| react-html | [directory](packages/react-html) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-html.svg)](https://badge.fury.io/js/%40shopify%2Freact-html) |
| react-hydrate | [directory](packages/react-hydrate) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-hydrate.svg)](https://badge.fury.io/js/%40shopify%2Freact-hydrate) |
| react-i18n | [directory](packages/react-i18n) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-i18n.svg)](https://badge.fury.io/js/%40shopify%2Freact-i18n) |
| react-i18n-universal-provider | [directory](packages/react-i18n-universal-provider) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-i18n-universal-provider.svg)](https://badge.fury.io/js/%40shopify%2Freact-i18n-universal-provider) |
| react-idle | [directory](packages/react-idle) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-idle.svg)](https://badge.fury.io/js/%40shopify%2Freact-idle) |
| react-import-remote | [directory](packages/react-import-remote) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-import-remote.svg)](https://badge.fury.io/js/%40shopify%2Freact-import-remote) |
| react-intersection-observer | [directory](packages/react-intersection-observer) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-intersection-observer.svg)](https://badge.fury.io/js/%40shopify%2Freact-intersection-observer) |
| react-network | [directory](packages/react-network) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-network.svg)](https://badge.fury.io/js/%40shopify%2Freact-network) |
| react-performance | [directory](packages/react-performance) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-performance.svg)](https://badge.fury.io/js/%40shopify%2Freact-performance) |
| react-router | [directory](packages/react-router) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-router.svg)](https://badge.fury.io/js/%40shopify%2Freact-router) |
| react-server | [directory](packages/react-server) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-server.svg)](https://badge.fury.io/js/%40shopify%2Freact-server) |
| react-server-webpack-plugin | [directory](packages/react-server-webpack-plugin) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-server-webpack-plugin.svg)](https://badge.fury.io/js/%40shopify%2Freact-server-webpack-plugin) |
| react-shortcuts | [directory](packages/react-shortcuts) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-shortcuts.svg)](https://badge.fury.io/js/%40shopify%2Freact-shortcuts) |
| react-testing | [directory](packages/react-testing) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-testing.svg)](https://badge.fury.io/js/%40shopify%2Freact-testing) |
| react-tracking-pixel | [directory](packages/react-tracking-pixel) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-tracking-pixel.svg)](https://badge.fury.io/js/%40shopify%2Freact-tracking-pixel) |
| react-universal-provider | [directory](packages/react-universal-provider) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-universal-provider.svg)](https://badge.fury.io/js/%40shopify%2Freact-universal-provider) |
| react-web-worker | [directory](packages/react-web-worker) | [![npm version](https://badge.fury.io/js/%40shopify%2Freact-web-worker.svg)](https://badge.fury.io/js/%40shopify%2Freact-web-worker) |
| rpc | [directory](packages/rpc) | [![npm version](https://badge.fury.io/js/%40shopify%2Frpc.svg)](https://badge.fury.io/js/%40shopify%2Frpc) |
| semaphore | [directory](packages/semaphore) | [![npm version](https://badge.fury.io/js/%40shopify%2Fsemaphore.svg)](https://badge.fury.io/js/%40shopify%2Fsemaphore) |
| sewing-kit-koa | [directory](packages/sewing-kit-koa) | [![npm version](https://badge.fury.io/js/%40shopify%2Fsewing-kit-koa.svg)](https://badge.fury.io/js/%40shopify%2Fsewing-kit-koa) |
| statsd | [directory](packages/statsd) | [![npm version](https://badge.fury.io/js/%40shopify%2Fstatsd.svg)](https://badge.fury.io/js/%40shopify%2Fstatsd) |
| useful-types | [directory](packages/useful-types) | [![npm version](https://badge.fury.io/js/%40shopify%2Fuseful-types.svg)](https://badge.fury.io/js/%40shopify%2Fuseful-types) |
| web-worker | [directory](packages/web-worker) | [![npm version](https://badge.fury.io/js/%40shopify%2Fweb-worker.svg)](https://badge.fury.io/js/%40shopify%2Fweb-worker) |
| with-env | [directory](packages/with-env) | [![npm version](https://badge.fury.io/js/%40shopify%2Fwith-env.svg)](https://badge.fury.io/js/%40shopify%2Fwith-env) |

### Gem Index

| package |     |     |
| ------- | --- | --- |
| quilt_rails | [directory](gems/quilt_rails) | [![Gem Version](https://badge.fury.io/rb/quilt_rails.svg)](https://badge.fury.io/rb/quilt_rails) |

## Want to contribute?

Check out our [Contributing Guide](./.github/CONTRIBUTING.md)

## Questions?

For Shopifolk, you can reach out to us in Slack in the `#web-foundation-tech` channel. For external inquiries, we welcome bug reports, enhancements, and feature requests via Github issues.

## License

MIT &copy; [Shopify](https://shopify.com/), see [LICENSE.md](LICENSE.md) for details.

<a href="http://www.shopify.com/"><img src="https://cdn.shopify.com/assets2/brand-assets/shopify-logo-main-8ee1e0052baf87fd9698ceff7cbc01cc36a89170212ad227db3ff2706e89fd04.svg" alt="Shopify" width="200" /></a>
