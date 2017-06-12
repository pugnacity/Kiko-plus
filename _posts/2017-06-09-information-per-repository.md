---
layout: post
title:  "Set git information per repository"
date:   2017-06-09
tags:  [ git, development]
---
Normally your git information like author name and e-mail address are stored in `~/.git.config`.
But you can set the information also for a  repository with the following commands in the repository
	git config user.name Sven
	git config user.email sven.winkelmann@blue1.at 

With `git config -l` you can verify your change.