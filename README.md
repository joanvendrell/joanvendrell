![ci](https://github.com/joanvend/academic-webpage/actions/workflows/ci.yml/badge.svg)
![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)
![License](https://img.shields.io/github/followers/joanvend.svg?style=social&label=Follow&maxAge=2592000)

# Webpage

Academic Website Template based on MKDocs.

## Development setup

> Note: you need at least Python 3.9 installed. This instructions are for Windows.

1. Create an environment under your workdir.
```
workdir> py -3.9 -m venv webpage_env
```
2. Activate the environment
```
workdir> .\webpage_env\Scripts\activate
```
3. Install dependencies
```
(webpage_env) workdir> python -m pip install -r requirements.txt
```
4. Serve your webpage at localhost:8000
```
(webpage_env) workdir> mkdocs serve
```

## Deployment - CI/CD

We use Github Actions to automate the deployment.

## References

- [MKDocs](https://www.mkdocs.org/)
- [MKDocs Material](https://squidfunk.github.io/mkdocs-material/)
- [MKDocs Material Github Actions](https://squidfunk.github.io/mkdocs-material/publishing-your-site/#with-github-actions-material-for-mkdocs)
