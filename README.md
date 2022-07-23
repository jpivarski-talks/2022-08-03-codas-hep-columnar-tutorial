# CoDaS-HEP

This repository contains three notebooks on [columnar data analysis](https://indico.cern.ch/event/1151367/timetable/#41-columnar-data-analysis), presented at CoDaS-HEP at 12:30pm on August 3, 2022 by Jim Pivarski and Ioana Ifrim.

## How to participate

You don't need to install anything on your computer to participate; I encourage everyone to join on Binder.

<p align="center">
  <a href="https://mybinder.org/v2/gh/jpivarski-talks/2022-08-03-codas-hep-columnar-tutorial/v1.0?urlpath=lab/tree/part-1.ipynb">
    <img src="https://mybinder.org/badge_logo.svg" alt="Launch Binder" height="40">
  </a>
</p>

**Binder tips:**

If your notebook becomes unresponsive, reconnect to the kernel or restart the kernel from the "Kernel" menu.

While working on exercises, keep a copy of your work-in-progress in a text editor, so that you don't lose them if the web page reloads. "Run → Run All Above Selected Cell" and "Kernel → Restart Kernel and Run up to Selected Cell" will rerun all of the code to get your Python session back to the state it was in before a page reload or kernel restart.

## If you _want_ to install and run on your computer

We use the libraries and versions listed in [environment.yml](environment.yml). You also need to install JupyterLab. You don't have to install the libraries with pip (you can use conda, for instance), and you don't need to use the exact versions that this tutorial has been pinned to, but you should probably use _at least_ those versions.

We won't spend any time in the tutorial session on installing libraries. If an installation on your computer doesn't work, switch to Binder by pressing the button above.

## Browsing the material online without Binder

If you want to see the notebooks online but don't want to execute them in Binder, the order is

   * [part-1.ipynb](part-1.ipynb): overview of programming paradigms and array-oriented in particular
   * [part-2.ipynb](part-2.ipynb): overview of tools for columnar data analysis of particle physics data
   * [project.ipynb](project.ipynb): set-up and challenge problems—discovering the Higgs boson

The default notebooks are unevaluated. To see static outputs from a previous run, look in the [evaluated](evaluated) directory.
