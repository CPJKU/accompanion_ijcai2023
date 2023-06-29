# ACCompanion Supplementary Material IJCAI 2023

This repository contains the supplementary material of the paper [The ACCompanion: Combining Reactivity, Robustness, and Musical Expressivity in an Automatic Piano Accompanist](https://arxiv.org/abs/2304.12939), accepted at IJCAI 2023.
This work was conducted at the [Institute of Computational Perception](https://www.jku.at/en/institute-of-computational-perception/) at JKU.

Visit the official [ACCompanion](https://github.com/CPJKU/accompanion) Repository


### Awards
This work was awarded the Science Breakthrough of the Year 2021 by the Falling Walls Foundation in Berlin. See [press release](https://falling-walls.com/press-releases/109869/), [talk](https://falling-walls.com/discover/videos/computer-accompanist-breaking-the-wall-to-computational-expressivity-in-music-performance/) and [demo](https://www.youtube.com/watch?v=KE6WhYxuWLk).


### Live Demos
- [J. Brahms "Hungarian Dance No.5 in F# minor"](https://www.youtube.com/watch?v=Wtxcqp-sQ_4)
- [F. Schubert "Rondo in A major D.951"](https://www.youtube.com/watch?v=qEocywdruco)


## Abstract

This paper introduces the ACCompanion, an expressive accompaniment system. Similarly to a musician who accompanies a soloist playing a given musical piece, our system can produce a human-like rendition of the accompaniment part that follows the soloist's choices in terms of tempo, dynamics, and articulation. The ACCompanion works in the symbolic domain, i.e., it needs a musical instrument capable of producing and playing MIDI data, with explicitly encoded onset, offset, and pitch for each played note. We describe the components that go into such a system, from real-time score following and prediction to expressive performance generation and online adaptation to the expressive choices of the human player. Based on our experience with repeated live demonstrations in front of various audiences, we offer an analysis of the challenges of combining these components into a system that is highly reactive and precise, while still a reliable musical partner, robust to possible performance errors and responsive to expressive variations. 


## Acknowledgments
This work is supported by the European Research Council (ERC) under the EU’s Horizon 2020 research & innovation programme, grant agreement No. 10101937 (”Wither Music?”).



## Cite Us

If you use this work please cite us:

```shell
@inproceedings{cancino2023accompanion,
  title={The ACCompanion: Combining Reactivity, Robustness, and Musical Expressivity in an Automatic Piano Accompanist},
  author={Cancino-Chac{\'o}n, Carlos and Peter, Silvan and Hu, Patricia and Karystinaios, Emmanouil and Henkel, Florian and Foscarin, Francesco and Varga, Nimrod and Widmer, Gerhard},
  booktitle={Proceeding of the International Joint Conference on Artificial Intelligence},
  year={2023}
}
```
