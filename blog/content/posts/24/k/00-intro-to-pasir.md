+++
title = '00 Intro to Pasir'
date = 2024-11-02T20:22:25+07:00
draft = false
tags = ['pasir']
authors = ['viridi']
url = '24k00'
+++
Create pasir as continuation of butiran, which has undetermined pause.

<!--more-->

It is now has Python and JavaScript parts, where the first is for calculation and the second is for visulization.

+ `03-nov-2024` Add [butiran](https://pypi.org/project/butiran/).
  - Create folder `butiran` in `src` for integration to pasir.
  - Unable to fix error [`11646202081`](https://github.com/dudung/pasir/actions/runs/11646202081).
+ `02-nov-2024` Create pasir.
  - Combine `src` (Python + JavaScript) and `blog` (Hugo) in a repo.
  - Fix default `hugo.yml` for GitHub Action.
    + Add `-s blog` after `run: | hugo`.
    + Modify `./public` to `./blog/public` in `path` of `Upload artifact`.
