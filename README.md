simpleSet
=========

## Description
A simple golang set because who wants to reinvent wheels all the time
when you really just want to solve problems?

## Status
[![Go Tests](https://github.com/sam-caldwell/simpleSet/actions/workflows/go-tests.yaml/badge.svg)](https://github.com/sam-caldwell/simpleSet/actions/workflows/go-tests.yaml)

## Methods

### `.Add(item string) error`

> Add a new item to the set and throw an error if it already exists.

### `.Count() int`

> Return a count of records

### `.Delete(item string) error`

> Delete an existing

### `.Has(item string) bool`

> Return true if item exists or false otherwise.

## Build / test
> For local builds, there is a `Makefile` but there is also a GitHub action for this 
> project.

`make test` - run tests 

