# Welcome

### About
My name is Ayaz and I’m a first year masters student studying music tech at NYU. I play Euphonium, compose, and create tools for other musicians. I’ve built MuseScore plugins and VSTs for DAWs, written music for short films and video games, and been published by Cimarron Music Press. My primary technical interests is in MIR, but I'm also interested in plugin/software development, DSP, and music animation. I’m classically trained, but my musical interests include Lo-fi, EDM, Jazz, and film/video game music. Take a look at my pinned repos, I love making READMEs for them.

Email: [ayazearley@gmail.com](mailto:ayazearley@gmail.com)  
LinkedIn: [linkedin.com/in/ayaz-earley-74b564323](www.linkedin.com/in/ayaz-earley-74b564323)
Youtube: [youtube.com/@AyazEarley](https://www.youtube.com/@AyazEarley)

Totally feel free to reach out if you want to connect :)

### Skills
- **Languages:** C++, C, Python, Java, JavaScript, TypeScript
- **Frameworks/Libraries:** JUCE, PyTorch, React, Manim, NumPy, Librosa, PyGame
- **Audio/Notation:** MuseScore 4, FL Studio, Audacity
- **Tools:** Git, CMake, Visual Studio

### What I'm currently working on

Currently I'm working on version 1.0 of Diesis, an open source C++ library for 31EDO operations. Microtonal music has been picking up traction in recent years, both by artists and music theorists. My goal is to create a versatile library that can support both plugin devs and researchers. Below is a list of features I'm implementing:

- Audio thread safe operations for use in real-time systems
- Usable with any division of the octave (with a focus on 31EDO in early versions)
- Basic set theory operations: transposition, inversion, modeOf, hardness, comparison, subset, etc.
- Built-in list of scales and chords, easily expandable as research deepens
- Graph theory representation of chord relationships, allowing for transformation based harmonic models
- .scl and .kbm file compatibility
