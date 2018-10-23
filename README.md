# _Software Engineering_ lecture materials

## Preface

This repository contains lecture materials (mostly slide sets) for an undergraduate course in software engineering. This course was initially held at [Bauhaus-Universität Weimar](https://www.uni-weimar.de/) in the winter semester 2014/15 for B.Sc. students in the [Computer Science and Media](http://www.uni-weimar.de/en/media/studies/computer-science-and-media-hci/medieninformatik-computer-science-and-media-bsc/) degree. Prerequisites are basic knowledge about fundamentals of computer science and good skills (theoretical as well as practical) in C++. 

_Comments, feedback and suggestions for improvement (including pull requests) are very welcome._

## License

Original copyright (c) 2015 by [Florian Echtler](http://www.uni-weimar.de/en/media/chairs/mobile-media/). All material is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/) ![CC-BY-SA-NC](https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png).

As a very brief summary, this means that you can freely use these materials as long as you:

* provide attribution to the original author(s)
* share your modifications under the same or a similar license
* only use them for non-commercial purposes (such as teaching a university course)

Where possible, I have tagged material from external sources with CC (also under a compatible CC license), PD (public domain material) or FU (material which I believe to be included as "fair use"). I've found that it's at times quite difficult to find suitable CC-compatible materials for inclusion, which is why I'm doing a "rolling release" - every time I've converted a new slide set, I will add it to the repository.

## Contents

The course currently spans 12 weekly sessions with the following topics:

* Introduction
* Best Practices: RCS, Testing, UML
* Object-Oriented Development Refresher
* Classic & Agile Development Models (2 sessions)
* Design Patterns (2 sessions)
* Code Quality
* Build Process & Debugging
* Requirements Engineering
* Testing/CI & Memory Layout
* Open Source Software

The course is usually accompanied by an exercise class every two weeks. As the exercise materials are part of the graded course assignments, I'm currently not including them in this public release.

## git and ODT

The files in this repository are in OpenDocument format. If you add the following lines to your `~/.gitconfig` file and install the `odt2txt` utility, you can use the regular `git diff` command to compare versions etc. (see also [here](http://www-verimag.imag.fr/~moy/opendocument/) for more details).

    [diff "odf"]
    	textconv = odt2txt
