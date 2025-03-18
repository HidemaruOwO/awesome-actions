<!-- THIS README IS CREATED BY HidemaruOwO/MicroRepository -->
<!-- SEE: https://github.com/HidemaruOwO/MicroRepository -->

<!-- YOU SHOULD RUN THIS COMMAND IF YOU USING VIM -->
<!-- :%s;HidemaruOwO/awesome-actions;USERNAME/REPONAME;g -->

# Awesome GitHub Actions 🌈

<!-- description -->

A GitHub Actions example for some languages and some applications.

## 🚀 Features

<!-- write your apps features-->
<!-- This "features" section assumes a generic REST API. Please modify it to fit your software. -->

- GitHub Actions examples
- Web Interface (planning)

## 🎯 Usage

Copy and paste it into your repository from the `actions/` directory as you like.

## 🌍 For contributer

This project follows a specific naming convention for files that need to be maintained, ensuring consistency and ease of management.

If you plan to add a CI workflow for building and artifacting Rust code, please make sure to place it in the designated directory:

**Both an explanation and the workflow file are required.**

`actions/rust/build-and-artifact/action.yaml` (workflow file)
`actions/rust/build-and-artifact/README.md` (user guide)

**Including the source code that the workflow depends on is preferable but not required.**

```
❯ tree
.
└── build-and-artifact
    ├── README.md (required)
    ├── action.yaml (required)
    # It is not required, but it is preferable if added.
    ├── Cargo.lock
    ├── Cargo.toml
    └── src
        └── main.rs
3 directories, 5 files
```

This helps keep the project structure organized and makes it easier for contributors to find relevant workflows. Following this convention also ensures that CI processes remain standardized across different programming languages used in the project.

> [!NOTE]
> Do not add non-functional workflows!
>
> When creating a Pull Request, please include the GitHub URL where the workflow has been executed to verify its functionality. Additionally, it is preferable to standardize workflow files.

## 📜 License

<div align="left" style="flex: inline" >
<a href="https://github.com/MakeNowJust/sushi-ware" >
<img src="https://img.shields.io/badge/License-SUSHI--WARE%20%F0%9F%8D%A3-blue.svg" alt="SUSHI-WARE LICENSE"
</a>
</div>

This project is licensed under [SUSHI-WARE LICENSE](licenses/SUSHI-WARE.txt).

A reference to the latest license should be used, even if the attached license is outdated of major versions.

## 🤝 Reference

This repository was created using the [MicroRepository](https://github.com/HidemaruOwO/MicroRepository) template.

- [HidemaruOwO/MicroRepository](https://github.com/HidemaruOwO/MicroRepository)
