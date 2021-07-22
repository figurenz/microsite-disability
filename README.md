# Figure.NZ Disability Hub
This is a fork of https://github.com/WikiNewZealand/microsite-template. GitHub will not allow forking via UI of own repositories, so the upstream/fork is handled locally.

When making structural changes to the microsite template, these changes will need to be applied locally via pulling upstream main and merging.

## Structure

This repo has two main layout files.
- Homepage, used for the homepage
- Content, used for all other pages

index.md generates the homepage.
Other top-level .md files generate additional top-level pages, such as an 'About' file.
Some versions of this site will also have secondary pages that are grouped together. This repo has a folder called "_topics" as an example. .md files added to the topics file can be used to generate secondary pages, or to provide additional metadata for linking and cards, or both.

## Setup

the config.yml file has a series of variables you'll need to set for your project. This includes the name, tracking code etc.

## Running the project

Once you've navigated to the code folder and installed necessary dependencies, run

```bundle exec jekyll serve```

## Design

This project uses SCSS. 

The top of the SCSS file has variables for colour, font, and background tile used.

### Templates

the 'Content' template is nested into the 'Homepage' one.

