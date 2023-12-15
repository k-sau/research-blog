+++
title = 'My First Post'
date = 2023-12-10T15:11:38+05:30
draft = true
+++

## Introduction

This is **bold** text, and this is *emphasized* text.

Visit the [Hugo](https://gohugo.io) website!  

```
var express = require('express');
var router = express.Router();

router.get('/', function(req, res, next) {
 	res.render('index')
});

router.post('/', function(req, res, next) {
	var profile = req.body.profile
 	res.render('index', profile)
});

module.exports = router;
```