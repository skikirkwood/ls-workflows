# Content workflows practice space

This repo contains the content model for a legal approval workflow. After importing it you can customize the roles and permissions in your space to get hands-on practice working with a custom content workflow.

You need to have previously installed the [Contentful CLI tools](https://github.com/contentful/contentful-cli) and executed the Login command.

![The content model for a custom offer page](./github-screenshot.png
 "The content model for a custom offer page")

### Get the JSON space export file

```
$ git clone https://github.com/skikirkwood/ls-workflows.git
```

### Import the JSON export into an empty space

```
$ contentful space import --space-id <your space ID> --content-file ./contentful-workflow-export.json
```

