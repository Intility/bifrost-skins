# Intility Bifrost Skins - Contribution Guide

## Issues with an existing theme

1. Create a new issue, and provide a descriptive title and description.
2. Fork this repo.
3. Create a new branch with the naming `issue/#<issue_id>`.
4. Fix the problem
5. Create a new pull request
   - Assign the original creator as the reviewer
6. Wait for the pull request to be merged.

## I want to contribute with a new skin

1. Create a new branch with the naming standard `feat/<lowercase_snakecase_name>` and checkout to it.
2. Create a new folder with the name of the tool
3. Add all files necessary to configure the tool to use your skin.
4. Add a README in your new folder where you describe all necessary steps on how to configure your tool to use your theme.
   - (Optional) Include one or more screenshots of your theme
5. Create a new pull request.
6. Merge your branch into `main`.

## Commit messages

All commits messages should follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary).

```text
<type>[optional scope]: <description>
[optional body]
[optional footer(s)]
```

Samples:

```text
fix(dotnet): fix ArgumentException when starting project based on template
```

```text
docs: add Google auth guide to all frameworks
```

```text
docs(contributing): add fastapi to example scopes
```

### Types

Accepted types are based on [the Angular convention](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#type):

- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)

Other types from the Angular convention can be used, should they be relevant.

### Scopes

Scopes should be the name of the framework or language affected. Should multiple languages or frameworks be affected, the scope might be omitted.

Current frameworks:

- **cra**
- **dotnet**
- **express**

For the **docs** type, the scope might additionally be the name of a markdown file in the root of the repository (in lowercase).

### Description

The description should

- use the imperative, present tense: "change" not "changed" nor "changes"
- not capitalize the first letter
- not use dot (.) at the end
