---
layout: post
title: "use redis with mysql"
date: 2014-09-20 20:36:55
comments: true
share: true
description: redis 与 mysql 配套使用时的一些问题及解决方案
tags:
- redis
- mysql
- nosql
---

为了减小mysql读的压力，通常加redis缓存节点，此过程中如何保证redis与mysql的数据一致性等边界性问题。