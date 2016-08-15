# Awesome ActionHero.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center"><img src="https://raw.github.com/evantahler/actionhero/master/public/logo/actionhero.png" height="300"/></p>

<p align="center">
	The Reusable, Scalable, and Quick node.js API Server!
</p>


> A curated list of amazingly awesome **ActionHero.js 14.0.0+** plugins, resources and shiny things.

<hr/>

## Table of Contents

- [Plugins](#plugins)
	- [API Features](#api-features)
	- [Authentication and Authorization](#authentication-and-authorization)
	- [Miscellaneous](#miscellaneous)
	- [Integrations](#integrations)
	- [ORM and Datamapping](#orm-and-datamapping)
	- [Security](#security)
- [Examples](#examples)
	- [Demo](#demo)
- [Resources](#resources)
	- [Books and Articles](#books-and-articles)
	- [Videos](#videos)
	- [Tutorials](#tutorials)
	- [Reading and Listening](#reading-and-listening)
	- [Internals Reading](#internals-reading)
	- [Help](#help)
- [Conferences](#conferences)
- [Contributing](#contributing)



# Plugins
One tiny note when installing plugins, remember to `link` them to your projects to enable them - use the following command 
`npm run actionhero link -- --name PLUGINNAME`.

## API Features
*Plugins enhancing API control and other features.*
- ~~[ah-ratelimit-plugin](https://github.com/innerdvations/ah-ratelimit-plugin) - Limit the amount of action requests.~~

## Authentication and Authorization
*Plugins for implementing authentication and authorization.*
- ~~[ah-jwtauth2-plugin](https://github.com/ifavo/ah-jwtauth-plugin) - This useful plugin is using Auth0 jsonwebtoken to allow token authentication of actions.~~
- ~~[ah-passport-plugin](https://github.com/neilstuartcraig/ah-passport-plugin) - Passport plugin for ActionHero.~~

## Miscellaneous
*Misc plugins for ActionHero.*
- ~~[ah-stats-plugin](https://github.com/evantahler/ah-stats-plugin) - collection of methods that allow you to store arbitrary statistics about your server.~~

## Integrations
*Third party node.js modules as plugins.*
- ~~[ah-airbrake-plugin](https://github.com/evantahler/ah-airbrake-plugin) - ActionHero client for airbrakeapp.com, capture and track your apps exceptions.~~
- ~~[ah-newrelic-plugin](https://github.com/evantahler/ah-newrelic-plugin) - ActionHero client for newrelic.com, pinpoint your apps performance issues.~~
- ~~[ah-nodemailer-plugin](https://github.com/panjiesw/ah-nodemailer-plugin) - send emails using nodemailer in ActionHero, has integrated mail template capability.~~

## ORM and Datamapping
*Plugins that implement object-relational mapping or data-mapping techniques.*
- [ah-sequelize-plugin](https://github.com/evantahler/ah-sequelize-plugin) - This plugin implements sequelize ORM for ActionHero!



# Examples

## Demo
*Code example (demo) applications and tools.*
- [Angular+ActionHero](https://github.com/evantahler/actionhero-angular-bootstrap-cors-csrf) - ActionHero + Angular + Bootstrap + CORS + CSRF Demo Site
- [EarlyAgain](https://github.com/evantahler/earlyagain) - Anonymous chat application.



# Resources

## Books and Articles
*Fantastic ActionHero-related (e)books and other reading material.*
- [Learn more about ActionHero](http://www.actionherojs.com/learn-more/) - Official learn more guide!

## Videos
*Fantastic ActionHero-related videos.*
- [Mark Tuckers ActionHero.js Series](https://www.youtube.com/watch?v=cxuK5QlavOw) - Tutorial videos to get you started by Mark Tucker.

## Tutorials
*Must-do tutorials.*
- [Official tutorial](https://github.com/evantahler/actionhero-tutorial) - This tutorial will guide you through the basics of ActionHero.js!

## Reading and Listening
*Documentation and ActionHero-releated reading and listening materials.*
- [Official blog](http://blog.evantahler.com) - The one who started it all! Evan Tahler has a blog right there.

## Internals Reading
*Reading materials related to the ActionHero internals and decisions.*
- [Support for plugin auto-registration](https://github.com/evantahler/actionhero/issues/727) - Discussion for a new plugin related feature.
- [Support for Nested Plugins](https://github.com/evantahler/actionhero/issues/727) - Discussion for a nested plugins support.



## Help
*Where to get help.*

- [Gitter Chat](https://gitter.im/evantahler/actionhero) - Live chat/discussion with other devs and core devs.
- [stackoverflow.com/questions/tagged/actionhero](http://stackoverflow.com/questions/tagged/actionhero) - This is for specific questions, ideally along with some example code.



# Conferences
*None so far.* [Help us arrange one.](https://gitter.im/evantahler/actionhero)



# Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.
