# Hello Jekyll

Lab project for Jekyll's step by step tutorial.

<https://gitlab.com/brlin/hello-jekyll>  
[![The GitLab CI pipeline status badge of the project's `main` branch](https://gitlab.com/brlin/hello-jekyll/badges/main/pipeline.svg?ignore_skipped=true "Click here to check out the comprehensive status of the GitLab CI pipelines")](https://gitlab.com/brlin/hello-jekyll/-/pipelines) [![GitHub Actions workflow status badge](https://github.com/brlin-tw/hello-jekyll/actions/workflows/check-potential-problems.yml/badge.svg "GitHub Actions workflow status")](https://github.com/brlin-tw/hello-jekyll/actions/workflows/check-potential-problems.yml) [![pre-commit enabled badge](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "This project uses pre-commit to check potential problems")](https://pre-commit.com/) [![REUSE Specification compliance badge](https://api.reuse.software/badge/gitlab.com/brlin/hello-jekyll "This project complies to the REUSE specification to decrease software licensing costs")](https://api.reuse.software/info/gitlab.com/brlin/hello-jekyll)

## References

The following material are referenced during the development of this project:

* [Step by Step Tutorial | Jekyll • Simple, blog-aware, static sites](https://jekyllrb.com/docs/step-by-step/)  
  The tutorial this lab project is following.
* [ports | Services top-level elements | Docker Docs](https://docs.docker.com/reference/compose-file/services/#ports)  
  For the Docker Compose syntax of exposing the service in the container to the host.
* [add glob support to include,exclude option by mccxj · Pull Request #743 · jekyll/jekyll](https://github.com/jekyll/jekyll/pull/743)  
  Explains the glob matching implementation in Jekyll's `exclude` configuration option.
* [fnmatch?( pattern, path, \[flags\] ) → (true or false) | Class: File (Ruby 2.5.5)](https://ruby-doc.org/core-2.5.5/File.html#method-c-fnmatch-3F)  
  Explains the usage of the glob matching patterns used in Jekyll's `exclude` configuration option.

## Licensing

Unless otherwise noted(individual file's header/[REUSE.toml](REUSE.toml)), this product is licensed under [the 4.0 International version of the Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/4.0/), or any of its more recent versions of your preference.

This work complies to [the REUSE Specification](https://reuse.software/spec/), refer the [REUSE - Make licensing easy for everyone](https://reuse.software/) website for info regarding the licensing of this product.
