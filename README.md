# random-nickname

## Introduction

get a random nickname


## install

```
$ composer require liuyupeng/random-nickname
```

## Demo

```
require __DIR__ . '/vendor/autoload.php';

use liuyupeng\randomnickname\Nickname;

$nkClass = new Nickname();
$nickname = $nkClass->getNickname();
```