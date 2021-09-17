# Simulation group

<p align="center">
  <img src="https://user-images.githubusercontent.com/22986666/129444178-6587decc-9d6e-4308-90fb-eaca528513e1.png" width="700px">
   <br>
  Image credit: <a href="https://people.ece.cornell.edu/land/courses/ece1810/LTspice/">cornell.edu</a>
</p>

Simulator: ~~LTSpiceIV~~ LTSpiceXVII - [download link](https://ltspice.analog.com/software/LTspiceXVII.exe)
   * It is available only for Windows but it works fine by using `wine` on Linux (tested on Linux Mint)

Reference Books:
   * Gayakwad (Opamps)
   * Boylestad (Analog circuits)

## Workplan

Here we list the steps involved in a weekly simulation exercise:

* First, we choose a chapter(s) from the reference books listed above, the reference books are chosen such that they contain dense information about the circuits and also contain information necessary for preparing a simulation in any standard circuit simulation tool.
    * We skip pure theory chapters from the books (but we do need the necessary context for understanding the intricacies of the circuits although such chapters are not actively involved in simulations)
* We choose a circuit from the book, at the start of the week each member chooses a circuit from the chapter chosen in previous step.
* We simulate the circuit in LTSpiceXVII
* Towards the end of the week, We prepare a short report (see [resources](https://github.com/rusty-electron/ltspice-simulation-group#resources) section for a latex template) that contains the details of the circuit as well as important information involved in preparing the simulation that can help while replicating it. This report is then peer-reviewed by another member.

* We also aim to post a simulation tutorial on [medium.com](https://medium.com), the timing of this task is flexible.
    * [ ] TODO: prepare a format for blog articles

> Seeking Simulation help is allowed during the week, other members can then assist him/her via screen-sharing or tool tips.

### Submission format

Place the Week X's files in the directory `./weekX` under the naming format `<username>-weekX.pdf`. Hence, if my username is `badbox4` and I am submitting for week 3, the report file should be place under the directory `week3` as `badbox4-week3.pdf`.

## Week-wise schedule

* [x] Week 1: Opamp with -ve feedback (first five chapters of Gayakwad) - [read](./week1)
* [x] Week 2: Frequency Response and General Linear Applications of Opamps - [read](./week2)
* [x] Week 3: Instrumentation Amplifiers and its applications - [read](./week3)
* [x] Week 4: General Linear Applications - [read](./week4)
* [ ] Week 5: Active Filters

## Resources

### Report template

Here is a [sample report template](https://www.overleaf.com/read/xdkhktjzpnfd), clone this and edit on [overleaf.com](https://overleaf.com) or download the `.tex` files and edit offline.

### adding LM741 spice model

The LM741 op-amp is quite frequently used in the examples of the Gayakwad book but it is not available by default in LTSpiceXVII so one can use this [guide](./add_LM741_LTspice.pdf) I found at eevblog's forums to add LM741 IC to LTSpiceXVII.

### Youtube playlists

#### LTspice

* [afrotechmods](https://www.youtube.com/playlist?list=PLB83D613334919AE6)
* [Fesz electronics](https://www.youtube.com/playlist?list=PLT84nve2j1g_wgGcm0Bv3K4RSl2Jdjsey)
* [eevblog](https://www.youtube.com/watch?v=FEGT5dUpdrc)
* [EE Topics](https://www.youtube.com/playlist?list=PL2w-HgusdsYMvIUsGTQJBV2i25r740uJx)

#### Opamps

* [Khan Academy](https://www.youtube.com/playlist?list=PLzUN9-WgjT3PcvDFD5cI9COE9E53CrcgA)
* [eevblog theory](https://www.youtube.com/watch?v=7FYHt5XviKc&list=PLvOlSehNtuHu2FviAaZaiyXwN41G4b1Lf)
