# Eriksen flanker task

An implementation of Eriksen flanker task in
[pyFlies](https://github.com/pyflies/pyflies/).

For details please see these two papers:

Eriksen, B. A., & Eriksen, C. W., Effects of noise letters upon the
identification of a target letter in a nonsearch task, Perception \&
psychophysics, 16(1), 143–149 (1974).

de Leeuw, J. R., JsPsych: A JavaScript library for creating behavioral
experiments in a Web browser, Behavior research methods, (), 1–12 (2014).


# Installing and running

To run this experiment in [PsychoPy
generator](https://github.com/pyflies/pyflies-psychopy):

1. Clone the git repo:
   ```
   git clone git@github.com:pyflies/EriksenFlanker.git 
   # or without github account
   git clone https://github.com/pyflies/EriksenFlanker.git
   ```

2. Go into the folder and crate Python virtual environment:
   ```
   cd EriksenFlanker
   python -m venv venv
   ```    
    
3. Activate Python virtual environment:
   ```
   source venv/bin/activate
   ```
   
4. Install PsychoPy generator for pyFlies:
   ```
   pip install pyflies-psychopy
   ```

5. Generate Python code:
   ```
   textx generate eriksen.pf --target psychopy --overwrite
   ```
   
6. Run it under PsychoPy:
   - [Install PsychoPy](https://www.psychopy.org/download.html)
   - Run
     ```
     python eriksen.py
     ```

## Notes

- If you change the pyFlies model `eriksen.pf` you can regenerate the code with
  step 5 and then rerun with `python eriksen.py`.
- You have to source the Python environment (step 3) for each new terminal session.
