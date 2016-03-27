<img src="https://avatars2.githubusercontent.com/u/514566?v=3&u=4615dfc4970d93dea5d3eaf996b7903ee6e24e20&s=140" align="right" />
---
![Logo of Rng](docs/logo-large.png)  
`RNG` (random number generator) for PHP  

| [![Build Status](https://travis-ci.org/clickalicious/Rng.svg?branch=master)](https://travis-ci.org/clickalicious/Rng) 	| [![Scrutinizer](https://img.shields.io/scrutinizer/g/clickalicious/Rng.svg)](https://scrutinizer-ci.com/g/clickalicious/Rng/) 	| [![clickalicious premium](https://img.shields.io/badge/clickalicious-premium-green.svg?style=flat)](https://www.clickalicious.de/) 	| [![Packagist](https://img.shields.io/packagist/l/clickalicious/Rng.svg?style=flat)](http://opensource.org/licenses/BSD-3-Clause) 	|
|---	|---	|---	|---	|
| [![GitHub issues](https://img.shields.io/github/issues/clickalicious/rng.svg?style=flat)](https://github.com/clickalicious/Rng/issues) 	| [![Code Coverage](https://scrutinizer-ci.com/g/clickalicious/Rng/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/clickalicious/Rng/?branch=master)  	| [![GitHub release](https://img.shields.io/github/release/clickalicious/Rng.svg?style=flat)](https://github.com/clickalicious/Rng/releases) 	| [![GitHub stars](https://img.shields.io/github/stars/clickalicious/rng.svg?style=flat)](https://github.com/clickalicious/Rng/stargazers)  	|


## Table of Contents

- [Features](#features)
- [Example](#example)
- [Requirements](#requirements)
- [Philosophy](#philosophy)
- [Versioning](#versioning)
- [Roadmap](#roadmap)
- [Security-Issues](#security-issues)  
- [License »](LICENSE)  
 

## Features

 - State of the Art & best practice PRNG implementation (64-Bit support)
 - Additional nice OOP abstraction to PHP core functionality
 - Stable + High-Quality
 - Clean, tested & well documented code
 - PHP 7.0 + HHVM ready!

[![SensioLabsInsight](https://insight.sensiolabs.com/projects/29d1f47a-0deb-47f0-9642-671bebb04795/big.png)](https://insight.sensiolabs.com/projects/29d1f47a-0deb-47f0-9642-671bebb04795)

## Example

Generate random number between 1 and 10 with OpenSSL random bytes (default)
```php
$generator = new Clickalicious\Rng\Generator();
$number    = $generator->generate(1, 10);
echo $number;
```

Generate random number between 1 and 10 with MCrypt random bytes
```php
$generator = new Clickalicious\Rng\Generator(Clickalicious\Rng\Generator::MODE_MCRYPT);
$number    = $generator->generate(1, 10);
echo $number;
```


## Requirements

 - PHP >= 5.3 (compatible up to version 5.6)


## Philosophy

This library provides a State of the Art PRNG implementation for PHP as well as an really nice abstraction to PHP's existing core functionality. No seeding required but good seed generator built in.


## Versioning

For a consistent versioning i decided to make use of `Semantic Versioning 2.0.0` http://semver.org. Its easy to understand, very common and known from many other software projects.


## Roadmap

- [ ] More tests
- [ ] Better visualization


## Security Issues

If you encounter a (potential) security issue don't hesitate to get in contact with me `opensource@clickalicious.de` before releasing it to the public. So i get a chance to prepare and release an update before the issue is getting shared. Thank you!


## Participate & Share

... yeah. If you're a code monkey too - maybe we can build a force ;) If you would like to participate in either **Code**, **Comments**, **Documentation**, **Wiki**, **Bug-Reports**, **Unit-Tests**, **Bug-Fixes**, **Feedback** and/or **Critic** then please let me know as well!
<a href="https://twitter.com/intent/tweet?hashtags=&original_referer=http%3A%2F%2Fgithub.com%2F&text=Rng%20-%20Random%20number%20generator%20for%20PHP%20%40phpfluesterer%20%23Rng%20%23php%20https%3A%2F%2Fgithub.com%2Fclickalicious%2FRng&tw_p=tweetbutton" target="_blank">
  <img src="http://jpillora.com/github-twitter-button/img/tweet.png"></img>
</a>

## Sponsors

Thanks to our sponsors and supporters:  

| JetBrains | Navicat |
|---|---|
| <a href="https://www.jetbrains.com/phpstorm/" title="PHP IDE :: JetBrains PhpStorm" target="_blank"><img src="https://resources.jetbrains.com/assets/media/open-graph/jetbrains_250x250.png" height="55"></img></a> | <a href="http://www.navicat.com/" title="Navicat GUI - DB GUI-Admin-Tool for MySQL, MariaDB, SQL Server, SQLite, Oracle & PostgreSQL" target="_blank"><img src="http://upload.wikimedia.org/wikipedia/en/9/90/PremiumSoft_Navicat_Premium_Logo.png" height="55" /></a>  |

#### Copyright
<div>Icons made by <a href="http://www.flaticon.com/authors/egor-rumyantsev" title="Egor Rumyantsev">Egor Rumyantsev</a> from <a href="http://www.flaticon.com" title="Flaticon">www.flaticon.com</a>             is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0">CC BY 3.0</a></div>