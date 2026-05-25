# odin project

> This repository contains all my projects from [The Odin Project](https://www.theodinproject.com/) curriculum. 

All projects are done in separate repositories and this repository acts as a catalog/porfolio showcasing all of the projects in the same place.

## Project Structure

```
odin-project/
│── README.md
│── foundations/
│   ├── project1/
│   ├── project2/
│── full-stack/
│   ├── project1/
│   ├── project2/
```
Clicking on each project will redirect you to the respective repository.

## Live Previews
For projects that can be showcased online, I'll be deploying them via **GitHub Pages**. Links will be added here as I complete them.

[Recipe site](https://k-m-shehan.github.io/odin-recipes/)
[Landing page](https://k-m-shehan.github.io/odin-landing-page/)

## Making sub projects
Add a sub-repo with `git submodule`.

```bash
git submodule add <repo-link> foundations/<new_dir_name>
```

Commit the newly added repo from the main repo.

In the instance that you make a change in a submodule, you will have to pull the changes from the module inside the main repo to update the changes (also commit after that).
