# v_package_template

A V template for packages, including MIT license and a dev container.

## Quick start guide

1. [Create a repository with this repository as a template](https://github.com/sakkke/v_package_template/generate).
2. Rename a file `./v_package_template.v` to `./your_package_name.v`.
3. Run a command `git ls-files | xargs -I{} sed -i s/v_package_template/your_package_name/g {}`.
4. Clean up a file `./your_package_name.v` and `./README.md`.

## License

MIT
