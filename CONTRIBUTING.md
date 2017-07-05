# Contribution Guidelines

Please ensure what each script file...

- Should be in a folder with it respective README.md file.
- Should provide a --help flag.
- Should pass the sanity check for availability of all commands.
- Should work independently of current working directory.

Also, and following the best practices...
- Make sure how the input is read: environment vs flags
- Print everything you're doing to the system but provide a --silent option if necessary and turn the display back on after silencing.
- Indicate progress with animations.
- Colour code your output.
- Do not prolong the life of your script unnecessarily.
- Clean up after yourself.
- Exit with different error codes.
- Print a new line to bid farewell.

### Updating your Pull Request

A lot of times, making a PR adhere to the standards above can be difficult.
If the maintainer notice anything that need to be changed, you will be asked to edit your PR before be merge it.
There's no need to open a new PR, just edit the existing one. If you're not sure how to do that, [here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md) on the different ways you can update your PR so that we can merge it.

Thank you for your suggestions!