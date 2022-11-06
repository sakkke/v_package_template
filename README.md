# v_package_template
A V template for **packages**, including MIT license, a dev container and GitHub Actions workflows.
If you want to create a standalone executable, you can see [v_standalone_template](https://github.com/sakkke/v_standalone_template).

## Quick start guide
1. [Create a repository with this repository as a template](https://github.com/sakkke/v_package_template/generate).
2. Clone a created package to a local environment.
3. Run a command `git ls-files | grep -v '^README.md$' | xargs -I{} sed -i s/v_package_template/your_package_name/g {}`.
4. Rename a file `./v_package_template.v` to `./your_package_name.v`.
5. Clean up a file `./your_package_name.v` and `./README.md`.

## License
MIT
