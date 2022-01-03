# Flabulous

Flabulous - the fabulous flat app

## About this repository

The main purpose of this repository is to serve as a playground for [me](https://github.com/fabianmue) to try out new technologies and learn new languages and programming concepts.

A secondary goal is to create a set of useful (digital) tools to be used by me and my flatmates in our everyday life.

## Ideas for potential features

- dynamic shopping list (potentially with push notifications for urgently needed things)
- todo list with assignable tasks
- some way to facilitate equalizing spending, creating a billing and potentially transferring the money

## Develop

### Prerequisites

- .NET 6.0 SDK: https://dotnet.microsoft.com/en-us/download

### Create basic Blazor app

`dotnet new blazorserver -f net6.0`

### Run Blazor app in watch mode

`dotnet watch run`

## Deploy

### create release

`dotnet publish -c Release`
