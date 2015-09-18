# Introduction

This project is simply a way to package up and distribute the Moodle Coding Standard which is defined in the
following project: [moodle-local_codechecker](https://github.com/moodlehq/moodle-local_codechecker)

This project does not attempt to do anything else.  If there are problems with the standard, then the problems should
be addressed in the `moodle-local_codechecker` project.  Once the problem is fixed, it can be synced from
`moodle-local_codechecker` into this project.

[![Latest Stable Version](https://poser.pugx.org/moodlerooms/moodle-coding-standard/v/stable)](https://packagist.org/packages/moodlerooms/moodle-coding-standard)
[![Total Downloads](https://poser.pugx.org/moodlerooms/moodle-coding-standard/downloads)](https://packagist.org/packages/moodlerooms/moodle-coding-standard)
[![License](https://poser.pugx.org/moodlerooms/moodle-coding-standard/license)](https://packagist.org/packages/moodlerooms/moodle-coding-standard)

# Install

Just add it to your project's `composer.json` file (`--dev` is optional based on your needs):

```
composer require --dev moodlerooms/moodle-coding-standard
```

# Usage

The following paths may change based on how things are installed, but basically you are looking for the path to
the CodeSniffer command and the path to the `moodle` directory of this project: 

```
vendor/bin/phpcs --standard=vendor/moodlerooms/moodle-coding-standard/moodle /path/to/moodle/plugin
```

# Credits

All praise should go to the contributors of
[moodle-local_codechecker](https://github.com/moodlehq/moodle-local_codechecker).

# License

This project is licensed under the GNU GPL v3 or later.  See the [LICENSE](LICENSE) file for details.
