+++
title = 'intro to pasir'
date = 2024-11-02T20:22:25+07:00
draft = false
tags = ['pasir']
authors = ['viridi']
url = '24k00'
+++
Create pasir as continuation of butiran, which has undetermined pause.

<!--more-->

Updates:

+ It is now has Python and JavaScript parts, where the first is for calculation and the second is for visulization.

Progress:

+ `09-nov-2024` Use a word for section instead of `##` prefix.
  - Current section words are Update, Progress, Info, Activities.
  - It is to accompany Tags, which is genereated by Hugo template.
+ `03-nov-2024` Add [butiran](https://pypi.org/project/butiran/).
  - Create folder `butiran` in `src` for integration to pasir.
  - Unable to fix error [`11646202081`](https://github.com/dudung/pasir/actions/runs/11646202081) while uploading package to [PyPI](https://pypi.org/).
+ `02-nov-2024` Create [pasir](https://github.com/dudung/pasir/tree/0245302c3eef38d6948c059ba458a0738f3e4a00).
  - Combine `src` (Python + JavaScript) and `blog` (Hugo) in a repo.
  - Fix default `hugo.yml` for GitHub Action.
    + Add `-s blog` after `run: | hugo`.
    + Modify `./public` to `./blog/public` in `path` of `Upload artifact`.
