# ember-cli-mocha

[![Build Status](https://travis-ci.org/ember-cli/ember-cli-mocha.svg?branch=master)](https://travis-ci.org/ember-cli/ember-cli-mocha)
[![npm version](https://badge.fury.io/js/ember-cli-mocha.svg)](https://badge.fury.io/js/ember-cli-mocha)
[![Ember Observer Score](https://emberobserver.com/badges/ember-cli-mocha.svg)](https://emberobserver.com/addons/ember-cli-mocha)

Mocha / Chai testing for your Ember CLI apps.

## Installation

Install ember-cli-mocha:

```sh
ember install ember-cli-mocha
```

## Usage

Tests rely on [ember-mocha](https://github.com/switchfly/ember-mocha) modules
and helpers. Please refer to that project to understand detailed usage.

## Compatibility

- `ember-cli-mocha` v0.14.0 requires at least Ember CLI v2.2.0 and Node.js 4
- Ember CLI v2.13+ requires at least `ember-cli-mocha` v0.13.3
- Ember CLI v2.12+ requires at least `ember-cli-mocha` v0.13.2

### Blueprints

Previous releases of this addon contained the blueprints necessary to generate
Mocha tests for your apps and addons. These blueprints have since been moved
into [ember.js](https://github.com/emberjs/ember.js/tree/master/blueprints),
[ember-data](https://github.com/emberjs/data/tree/master/blueprints) and
[ember-cli-legacy-blueprints](https://github.com/ember-cli/ember-cli-legacy-blueprints/tree/master/blueprints).

Recent releases of Ember CLI contain `ember-cli-legacy-blueprints` by default.
If you are using an older release then please add the
`ember-cli-legacy-blueprints` dependency manually to your project.

## Copyright and License

Copyright 2014 Switchfly

This product includes software developed at
Switchfly (http://www.switchfly.com).

NOTICE: Only our own original work is licensed under the terms of the Apache
License Version 2.0. The licenses of some libraries might impose different
redistribution or general licensing terms than those stated in the Apache
License. Users and redistributors are hereby requested to verify these
conditions and agree upon them.
