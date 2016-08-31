<!--
title: Creating Serverless Services
description: Creating a Serverless Service
layout: Page
-->

# Creating a service

Let's create our first Serverless service!

## Creating our service

You can create a service based on a specific template that specifies which provider and runtime to use.

To create a service with a `nodejs` runtime running on `aws` just pass the `aws-nodejs` template to the create command:

```
serverless create --template aws-nodejs
```

This will create a service and generate `serverless.yml` and `handler.js` files in the current
working directory.

You can also check out the [create command docs](../cli-reference/create.md) for all the details.

## Open the service inside your editor

Let's take a closer look at the skeleton Serverless has created for us.

You'll see the following files in your working directory:
- `serverless.yml`
- `handler.js`

### serverless.yml

This is our core service file. You can see the name of our service, the provider and the first function inside the
`functions` definition which points to the `handler.js` file.

If you want to learn more about the `serverless.yml` file you might
want check out our [in depth guide](../understanding-serverless/serverless-yml.md).

### `handler.js`

The `handler.js` file includes a function skeleton which returns a simple message. The function definition in
`serverless.yml` will point to this `handler.js` file and the function inside of it.

## Conclusion

We've just created our very first service with one simple `create` command. With that in place we're ready to deploy
our service (which now includes one example function) to our provider (in this case Amazon Web Services).

[Next step > Deploying our service](./3_deploying-services.md)
