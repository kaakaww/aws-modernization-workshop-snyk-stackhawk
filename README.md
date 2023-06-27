# StackHawk / Snyk AWS Modernization Workshop

> While under development, this site is temporarily posted to https://kaakaww.github.io/aws-modernization-workshop-snyk-stackhawk/.

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

To leverage themes already in this project:
```shell
git submodule init
git submodule update
```

## File Structure

At the moment, we are not sure what the difference between `*.ee.md` and `*.md` files are, but let's keep these contents in-sync.
Make your edits to `*.md`, then copy pasta (✨🍝✨)to `*.ee.md`.

## Content Layout

Module 1: What's the problem, what will we cover, who are the players, what will we do?
Module 2: Any specific AWS things to setup
Module 3: Partner Setup (How do you get rolling with StackHawk & Snyk)
Module 4: The workshop content.
