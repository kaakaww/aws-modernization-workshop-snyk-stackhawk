# StackHawk / Snyk AWS Modernization Workshop

This is an AWS Modernization Workshop that guides users through the process of setting up a build pipeline with automated DAST, SAST, and SCA security testing.

## Installing Hugo

This workshop is a Hugo static website. Hugo sites use the `hugo` CLI to build, develop, and deploy static sites based on Markdown docs. To work with this content, you should [install Hugo](https://gohugo.io/installation/). On a Mac, you can use Homebrew.

```shell
brew install hugo
```

## Local Development

The easiest way to set up a local development environment is to bring up in docker with the following command:

```shell
docker compose up
```

This will build the site with live reloading for any files you change.

You can achieve the same effect using the `hugo` CLI.

```shell
hugo server
```

## Build the Site

Then you can build the site with Hugo.

```shell
hugo
```

## Importing Themes

This workshop uses the Hugo theme, `hugo-theme-learn`. You may want to update it from time to time.

```shell
cd themes/hugo-theme-learn
git submodule update
```