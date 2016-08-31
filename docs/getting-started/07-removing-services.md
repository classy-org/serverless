<!--
title: Removing Services
description: How to remove a deployed service
layout: Page
-->

# Removing a service

The last step we want to introduce in this guide is how to remove the service.

##  Removing our service

Removal is done with the help of the `remove` command. Just run `serverless remove` to trigger the removal process.

Serverless will start the removal and informs you about it's process on the console.
A success message is printed once the whole service is removed.

**Note:** The removal process will only remove the service on your providers infrastructure. The service directory will still remain on your local machine so you can still modify and (re)deploy it to another stage, region or provider later on.

## Conclusion

We've just removed the whole service from our provider with a simple `serverless remove` command.

## What's next?

Check out the [examples folder](../_examples/README.md) for ideas of the types of serverless services and applications you can build
