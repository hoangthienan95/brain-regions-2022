# Things to change after cloning the template

- change project name in `pyproject.toml`
- poetry install (need previous step to be done for the current project to install)
- Follow [nbdev tutorial | nbdev](https://nbdev.fast.ai/tutorial.html#Note-if-using-a-subdirectory-to-contain-.ipynb-files-instead-of-the-project-root)
	- settings.ini
		- Change `lib_name` and other settings
		- Choose `doc_base_url` based on public or private page
	- set up git hooks using [nbdev_install_git_hooks](https://nbdev.fast.ai/cli.html#nbdev_install_git_hooks )
	- `nbdev_build_lib`
	- `nbdev_build_docs`
- Enable caching again in `.github/workflows/main.yml`
- `git add .`
- `git commit -m “Configure package from template”`
- Set up GitHub pages


# nbdev template

Use this template to more easily create your [nbdev](https://nbdev.fast.ai/) project.

_If you are using an older version of this template, and want to upgrade to the theme-based version, see [this helper script](https://gist.github.com/hamelsmu/977e82a23dcd8dcff9058079cb4a8f18) (more explanation of what this means is contained in the link to the script)_.
