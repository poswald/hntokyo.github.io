# hntokyo.github.io
HNTokyo community site


## Branches

The `src` branch contains the python source files for the Nikola static site 
generator. The `gh-pages` branch contains just the generated site and is 
[automatically deployed][1] by Github (via an action).

[1][https://github.com/poswald/hntokyo.github.io/settings/pages]

## Steps
- Make edits and save
- run `cd hntokyo && nikola build`
- run `nikola github_deploy`

