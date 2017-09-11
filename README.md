# Contentful Reference Quick Select

![Radio link UI extension](./example.gif "Radio link UI extension")

Quick and dirty example on how to change the "look" of the Contentful Reference Field

## Installation

```sh
git clone git@github.com:contentful-developer-relations/ui-reference-quick-select.git
cd ui-reference-quick-select
npm install
```

### Configure

Create a configuration file with your credentials for Contentful.

```sh
cp env.example .env
```

Open `.env` in a editor of your liking and add your Contentful space ID, and management token. [Learn how to obtain a token](https://www.contentful.com/developers/docs/references/authentication/#getting-an-oauth-token).

Load environment variables

```sh
source .env
```

### Create

```sh
npm run create
```

Create task will register the extension in your space on Contentful.

### Update

```sh
npm run update
```

Update task will upload the extension to your space on Contentful.

## License

Copyright &copy; Contentful Developer Relations

Licensed under the [MIT license](https://github.com/contentful/developer-relations/ui-country-select/blob/master/LICENSE).