# Project Title

This is an exercise where we customize an video player, based on the 30 days Javascript challenge.

## Getting Started

Use the controls to perform actions on the video.

## Demo

## [Custom Player](https://danielgarciaguillen.github.io/customplayer/)
![Custom Player](/image/customplayer.jpg?raw=true "Custom Player")


## Learnings

* How to select documents with:

```
const player = document.querySelector('.player');
const video = player.querySelector('.viewer');
const progress = player.querySelector('.progress');
const progressBar = player.querySelector('.progress__filled');
const toggle = player.querySelector('.toggle');
const skipButtons = player.querySelectorAll('[data-skip]');
const ranges = player.querySelectorAll('.player__slider');
```
* How to toogle play with:
```
function togglePlay() {
  const method = video.paused ? 'play' : 'pause';
  video[method]();
}
```

## Built With

* Vanilla Javascript
* Css
* Html
