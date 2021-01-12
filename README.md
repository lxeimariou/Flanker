# Eriksen flanker task

An implementation of Eriksen flanker task in
[pyFlies](https://github.com/pyflies/pyflies/).

For details please see these two papers:

Eriksen, B. A., & Eriksen, C. W., Effects of noise letters upon the
identification of a target letter in a nonsearch task, Perception \&
psychophysics, 16(1), 143–149 (1974).

de Leeuw, J. R., JsPsych: A JavaScript library for creating behavioral
experiments in a Web browser, Behavior research methods, (), 1–12 (2014).


To regenerate the code for [PsychoPy](https://www.psychopy.org/) from the
pyFlies model run:

    textx generate eriksen.pf --target psychopy --overwrite

To generate the code you must have pyFlies and [PsychoPy
generator](https://github.com/pyflies/pyflies-psychopy) installed.

To run the experiment:

    python eriksen.py

To run the experiment you must have PsychoPy installed.
