# templates-hub
The Templates Hub is the place to collect software templates based on [cookiecuters](https://cookiecutter.readthedocs.io/en/stable/index.html).

This collection is used by the Templates Hub service, running at [https://templates.services.fedcloud.eu](https://templates.services.fedcloud.eu). Users can (search), list available templates, choose a template of their interest, and generate software project based on the selected template: simply fill out the corresponding web form and receive zip file with the customized startup software project.

## How to add a new template entry
The template records are collected in this github repository. In order to add a new entry, one has to create [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) which will be reviewed by our members.

1. Fork this repository
2. (optional) Add a logo for your cookiecutter template, i.e. an image file in the `pictures/` directory or use e.g. `pictures/cookiecutter_simple_small.png`
3. Create a new JSON file keeping convention `githubuser-cookiecutter_repository.json`
4. Fill the content following the example below
5. Commit your changes
6. Create [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to add your new file in our repository

Here is the JSON example for adding a new cookiecutter template entry:
```
{
    "title": "Template name",
    "summary": "Short summary",
    "tags": [],
    "picture": "pictures/your_cookiecutter_logo.png",
    "gitLink": "https://github.com/user/repository",
    "gitCheckout": "main"
}
```
