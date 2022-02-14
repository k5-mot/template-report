# Report Template

## Features

Template of report by LaTeX.

## Demo

## Usage

### Makefile

|Command|Feature                            |
|:--:|:--:|
|default|View help for Makefile.            |
|all    |View a PDF file.                   |
|view   |View a PDF file.                   |
|build  |Generate a PDF file from TeX files.|
|clean  |Remove generated files.            |
|rebuild|Regenerate a PDF file.             |
|help   |View help for Makefile.            |

```zsh
# Generate a PDF file from TeX files.
make build

# View a PDF file.
make view

# View help for Makefile.
make help
```

### GitHub Actions

```zsh
# Registry a location of remote repository.
git remote add origin git@github.com:[username]/[repository].git

# Label tag name.
git tag [tag_name(cf: v1.0.0)]

# Push tag to remote repository.
git push origin [tag_name]

# Release a PDF file in GitHub Releases.
```

## Note

Good luck!!!

## Author

* k5-mot

## License

Copyright (c) 2021 k5-mot All Rights Reserved.

"k5-mot/report_template" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

