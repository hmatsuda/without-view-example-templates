# Without View Example Templates

This provides a set of templates for `apm init` to generate a new Atom package without view related code.

These templates are an alternative to a package generated in atom via the `package-generator:generate-package` command, without view related files and code.

## Usage

You supply the templates in the `templates` dir to `apm init`

```
git clone git@github.com:hmatsuda/without-view-example-templates.git
apm init -p my-package-name --template without-view-example-templates/templates
```

Now you should have a new package in the `my-package-name` directory. Now you can link it and see it in action

```
cd my-package-name
apm install
apm link -d
atom -d
```

In Atom use the `ctrl-alt-o` key command to see it in action.
