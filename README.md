# laravelGraphQL
Simple application to understand basic and core fundamental of laravel with GraphQL(Light House)

**Installation**

Install via composer

_composer require nuwave/lighthouse_

**Publish the default schema**

Lighthouse includes a default schema to get you going right away. Publish it using the following artisan command:

_php artisan vendor:publish --tag=lighthouse-schema_

**IDE Support**

Lighthouse makes heavy use of the SDL and utilizes schema directives. To improve your editing experience, you can generate a definition file with an artisan command:

_php artisan lighthouse:ide-helper_

**Install GraphQL DevTools**

To make use of the amazing tooling around GraphQL, we recommend installing GraphQL Playground (opens new window).

_composer require mll-lab/laravel-graphql-playground_

After installation, visit /graphql-playground to try it.

You can use any GraphQL client with Lighthouse, make sure to point it to the URL defined in the config. By default, the endpoint lives at /graphql.
