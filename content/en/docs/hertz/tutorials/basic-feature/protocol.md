---
title: "Protocol"
date: 2022-05-23
weight: 3
description: >

---

## TLS
Hertz Server & Client currently only supports TLS for the standard network library, and the support for the [Netpoll](https://github.com/cloudwego/netpoll) network library is still on the way.
Usage Reference: [Hertz Example](/zh/docs/hertz/tutorials/example/) and [Hertz Config](/zh/docs/hertz/reference/config/)

## ALPN
ALPN can be switched on or off with a switch after TLS is enabled.(depending on whether all required protocol Servers are currently registered via Protocol Suite)

## WebSocket
The internal production environment is already in use, so please look forward to hearing from us. Please feel free to raise an issue if you need it.

## HTTP2
The internal production environment is already in use, so please look forward to hearing from us. Please feel free to raise an issue if you need it.