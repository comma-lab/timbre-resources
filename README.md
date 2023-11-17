# Timbre resources

This is a living document of resources to support digital instrument makers and music technologists work with and design timbre. Community contributions via pull requests are welcomed.

[Communication Acoustics Lab](https://comma.eecs.qmul.ac.uk/), [Centre for Digital Music](http://c4dm.eecs.qmul.ac.uk/), Queen Mary University of London

### Audio content analysis

[Timbre Toolbox](https://github.com/MPCL-McGill/TimbreToolbox-R2021a) | MATLAB toolbox for computing audio descriptors.

[MIR Toolbox](https://github.com/olivierlar/mirtoolbox) | Low and high level audio feature extraction. It is written in Matlab and includes preprocessing, classification, similarity measures and clustering functionality.

[LibXtract](http://jamiebullock.github.io/LibXtract/documentation/) | Libxtract can extract low level features in real time. It is written in C, Max-MSP, Pure Data, Super Collider and Vamp.

[Essentia](http://essentia.upf.edu/) | An open-source C++ library for audio analysis and audio-based music information retrieval released under the Affero GPLv3 licence (also available under proprietary licence upon request) which has been developed by the Music Technology Group in Universitat Pompeu Fabra. Essentia was awarded with the Open-Source Competition of ACM Multimedia in 2013.

[Sonic Visualiser](https://www.sonicvisualiser.org/) | A free, open-source application for Windows, Linux, and Mac, designed to be the first program you reach for when you want to study a music recording closely. It's designed for musicologists, archivists, signal-processing researchers, and anyone else looking for a friendly way to look at what lies inside the audio file.

[Spear](https://www.klingbeil.com/spear/) | SPEAR is an application for audio analysis, editing and synthesis. The analysis procedure (which is based on the traditional McAulay-Quatieri technique) attempts to represent a sound with many individual sinusoidal tracks (partials), each corresponding to a single sinusoidal wave with time varying frequency and amplitude.

[Audio Features Ontology](https://motools.sourceforge.net/doc/audio_features.html) | This ontology expresses some common concepts to represent some features of audio signals. It mainly relies on the Event ontology, in order to classify particular parts of the timeline backing an audio signal. It also supports dense features, such as chromagrams, onset detection function etc.

### Machine learning and AI

[SP-Tools](https://rodrigoconstanzo.com/sp-tools/) | A set of machine learning tools that are optimised for low latency and real-time performance. The tools can be used with [Sensory Percussion sensors](http://sunhou.se/), ordinary drum triggers, or any audio input.

[FluCoMa](https://www.flucoma.org/) | The FluCoMa software consists of objects for decomposing and describing audio, and for manipulating collections of sonic data by querying, matching, learning and transforming. The complete toolkit is available for Max, SuperCollider and Pure Data, and the decomposition / description tools are available for the command line.

[nn~](https://acids-ircam.github.io/nn_tilde/) | At its core, nn~ is a translation layer between Max/MSP or PureData and the [libtorch c++ interface for deep learning](https://pytorch.org/). Alone, nn~ is like an empty shell, and requires pretrained models to operate. You can find a few [RAVE](https://github.com/acids-ircam/rave) models [here](https://acids-ircam.github.io/rave_models_download), or a few [vschaos2](https://github.com/acids-ircam/vschaos2) models [here](https://www.dropbox.com/sh/avdeiza7c6bn2of/AAAGZsnRo9ZVMa0iFhouCBL-a?dl=0). Using nn~ for PureData, RAVE can be used in realtime on embedded platforms, such as Bela or Raspberry Pi 4.

[neutone.space](https://neutone.space/) | A platform where researchers can share real-time AI audio processing models for creators to experiment with transformative AI audio instruments.

### Datasets

[SOL](https://forum.ircam.fr/collections/detail/sol-instrumental-sounds-datasets/) | Ircam instrumental sound database coming from the Studio On Line project.

[Nsynth](https://magenta.tensorflow.org/datasets/nsynth) | 305,979 musical notes, each with a unique pitch, timbre, and envelope.

[Freesound](https://freesound.org/) | a collaborative collection of 618,244 free sounds

[OpenMIC-2018](https://zenodo.org/records/1432913#.W6dPeJNKjOR) | 20000 audio clips with annotations of the presence or absence of 20 instrument classes

[URMP](http://labsites.rochester.edu/air/projects/URMP.html) | 44 pieces of orchestral recordings with note-level and frame-level annotations

[MIS](https://theremin.music.uiowa.edu/MIS.html) | single instrument notes with different playing techniques

[Medley-solos-DB](https://zenodo.org/records/2582103) | an instrument recognition dataset, audio extracted from MedleyDB and solosDB

### Miscellaneous

[TOR](https://timbreandorchestration.org/) | The Timbre and Orchestration Resource (TOR) is an open-access web platform dedicated to providing tools, materials, and resources for the analysis, creation and teaching of timbre and orchestration.

[SpeaK (Max)](https://forum.ircam.fr/projects/detail/speak/) & [(Web)](https://forum.ircam.fr/projects/detail/speak-web/) | SpeaK proposes a collaborative platform for organising, presenting and sharing sound lexicons combining words, definitions and sound examples.

[Timbre & Formants (English)](https://muwidb.univie.ac.at/orchestration/) & [(enlarged German version)](https://muwiserver.synology.me/dynamic/timbremaps.htm) | A collection of interactive audio examples by Christoph Reuter at the University of Vienna’s Musicological Department.

### Readings and talks

_This is a small selection of conference proceedings, including video recordings of talks, and books that introduce contemporary academic discourse on timbre._

[Nothing but Noise: Timbre and Musical Meaning at the Edge](https://global.oup.com/academic/product/nothing-but-noise-9780190495107?cc=us&lang=en&#) | First book to present an interdisciplinary theory on the contribution of timbre to musical meaning and affect.

[The Oxford Handbook of Timbre](https://academic.oup.com/edited-volume/36334) | First large-scale edited volume devoted to the study of timbre. Brings together philosophical, historical, cultural, technological, and analytical perspectives.

[Timbre: Paradox, Materialism, Vibrational Aesthetics](https://www.bloomsbury.com/uk/timbre-9781501365812/) | This book also presents a multi-disciplinary approach to timbre, assessing the acoustic, corporeal, performative, and aesthetic dimensions of tone color in Western music practice and philosophy.

[The Race of Sound: Listening, Timbre, and Vocality in African American Music](https://www.dukeupress.edu/the-race-of-sound) | Timbre might not be as innocent as you might think. Nina Eidsheim examines singers Marian Anderson, Billie Holiday, and Jimmy Scott as well as the vocal synthesis technology [Vocaloid](https://www.vocaloid.com/en/) to show how listeners carry a series of assumptions about the nature of the voice and to whom it belongs.

[Timbre: Acoustics, Perception, and Cognition](https://link.springer.com/book/10.1007/978-3-030-14832-4) | First edited volume dedicated to a comprehensive and authoritative presentation of timbre perception and cognition research and the acoustic modelling of timbre.

[The Relentless Pursuit of Tone: Timbre in Popular Music](https://global.oup.com/academic/product/the-relentless-pursuit-of-tone-9780199985227) | First book dedicated to the subject of timbre in popular music, from San Francisco's early rave scene to the twang of country banjos and the sheen of hip-hop strings.

[The Orchestral Revolution: Haydn and the Technologies of Timbre](https://www.cambridge.org/core_title/gb/434594) | By focusing upon Joseph Haydn's innovative strategies of orchestration and tracing their reception and influence, Emily Dolan shows that the consolidation of the modern orchestra radically altered how people listened to and thought about the expressive capacity of instruments.

[From Music to Sound: The Emergence of Sound in 20th- and 21st-Century Music](https://www.routledge.com/From-Music-to-Sound-The-Emergence-of-Sound-in-20th--and-21st-Century-Music/Solomos/p/book/9781032087160#:~:text=From%20Music%20to%20Sound%20is,to%20a%20culture%20of%20sound.) | Makis Solomos shows how new music, from Debussy to electronica, began a change of listening paradigm, moving from a culture centred on the note to a culture of sound.

[The International Conference on Timbre](https://timbreconference.org/) | A new triennial interdisciplinary forum for exchanging novel perspectives and forging collaborations across different disciplines to help address challenges in our understanding of timbre from empirical, theoretical, and computational perspectives.

[Timbre Topologies - Perceptual and Conceptual Spaces](https://medienarchiv.zhdk.ch/sets/scs_timbre-topologies) | This symposium took place at the Zurich University of the Arts in February 2023, with a focus on spatial models for timbre.

[Analysis and Description of Timbre in Fixed Music](https://musinf.univ-st-etienne.fr/recherches/colloque_timbre/resources.html) | A mixture of music theorists, psychologists, and technologists came together in February 2021 at the Université Jean-Monnet Saint-Étienne in France to talk timbre.

[Timbre 2018: Timbre is a Many-Splendored Thing](https://www.mcgill.ca/timbre2018/) | In July 2018 the major timbre and orchestration researchers from around the world came together in Montreal for a conference about the study and deployment of timbre in music.
[[proceedings](https://www.mcgill.ca/timbre2018/files/timbre2018/timbre2018_proceedings.pdf)] [[videos of research keynote lectures](https://www.mcgill.ca/timbre2018/program)]

[Berlin Interdisciplinary Workshop on Timbre](https://www.youtube.com/playlist?list=PL9-WvglIK10jCMN3uEs4L7_aIt6B6GV1g) | In January 2017 young and established timbre researchers gathered at the [Berlin Museum of Musical Instruments](https://www.museumsportal-berlin.de/en/museums/musikinstrumenten-museum-simpk/) to assess the current state of the art in multi-disciplinary research on timbre.

[Workshop on Musical Timbre](https://musictimbre.wp.imt.fr/) | An informal, 1-day workshop at Télécom ParisTech in November 2014, aimed at bringing together researchers in MIR, music cognition, musical acoustics, audio signal processing, computer music and related fields, to discuss mutual interests, foster community, and encourage collaboration.
