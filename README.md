# sequelize-aws-x-ray-pg

The `sequelize-aws-x-ray-pg` module is a [`Sequelize`](http://sequelizejs.com/) extension for [AWS X-Ray](https://aws.amazon.com/xray/) to capture PostgreSQL queries.
This module requires the `pg` module.

## Installation

```
npm install --save sequelize-aws-x-ray-pg
```

## Usage

```
var Sequelize = require('sequelize');

var db = new Sequelize({
    dialect: 'postgres',
    dialectModulePath: 'sequelize-aws-x-ray-pg',
});
```
