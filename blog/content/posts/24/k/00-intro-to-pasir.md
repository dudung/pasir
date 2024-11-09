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

+ `10-nov-2024` Create fresh repository.
  - Clone pasir to testpasir.
  - Rename pasir to old-pasir and testpasir to pasir.
  - Test blog built with Hugo, still error [`11760110667`](https://github.com/dudung/pasir/actions/runs/11760110667/job/32760300240).
+ `09-nov-2024` Use a word for section instead of `##` prefix.
  - Current section words are Update, Progress, Info, Activities.
  - It is to accompany Tags, which is genereated by Hugo template.
  - Still unable to fix error [`11753616655`](https://github.com/dudung/pasir/actions/runs/11753616655/job/32746705870) while deploying to [PyPI](https://pypi.org/).
  - Similar GitHub Action works on [`11753526587`](https://github.com/dudung/remah/actions/runs/11753526587/job/32746507721).
  - Try a solution but still not works [`11753616655`](https://github.com/dudung/pasir/actions/runs/11753616655/job/32750716145).
  - It works on new repo with [`11755638995`](https://github.com/dudung/testpasir/actions/runs/11755638995/job/32750903513)
+ `03-nov-2024` Add [butiran](https://pypi.org/project/butiran/).
  - Create folder `butiran` in `src` for integration to pasir.
  - Unable to fix error [`11646202081`](https://github.com/dudung/pasir/actions/runs/11646202081) while uploading package to [PyPI](https://pypi.org/).
+ `02-nov-2024` Create [pasir](https://github.com/dudung/pasir/tree/0245302c3eef38d6948c059ba458a0738f3e4a00).
  - Combine `src` (Python + JavaScript) and `blog` (Hugo) in a repo.
  - Fix default `hugo.yml` for GitHub Action.
    + Add `-s blog` after `run: | hugo`.
    + Modify `./public` to `./blog/public` in `path` of `Upload artifact`.
