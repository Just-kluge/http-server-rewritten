# Secure HTTP Server Lite

## Overview

This project is a lightweight reimplementation of core functionalities from http-server, with additional security enhancements.

## Features

* Static file serving
* Safe path resolution
* Basic MIME type support

## Security Enhancements

* Path traversal protection
* Secure HTTP headers
* Access logging for audit

## Motivation

Existing lightweight HTTP servers often lack built-in security protections. This project aims to improve security and auditability while keeping the implementation minimal.

## Usage

```bash
node bin/server.js ./public
```

## Future Work

* Add HTTPS support
* Add rate limiting
* Improve MIME detection
