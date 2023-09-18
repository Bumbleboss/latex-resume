## About
The entire list of my resumes made in LaTeX! They are separated by specialization, each with their own layout for good content flow.

You can view the generated documents on my [portfolio](https://bumbleboss.xyz/about/).

## Structure
Each resume is considered a layout, and each layout has their sections in a separate file. The sections are contained inside a directory based on specialization.

For common content (e.g. LaTeX premable), they are simply put inside the content directory. Any assets like images, icons, and fonts are within the assets directory.

Structure:
```
├── assets
│   ├── fonts
│   │   ├── comic-sans.ttf
│   │   └── ...
│   └── meow.png
├── content
│   ├── specialztion-1
│   │   ├── section-1.tex
│   │   ├── section-2.tex
│   │   └── ...
│   ├── specialztion-2
│   │   └── ...
│   └── preamble.tex
├── layout-1.tex
├── layout-2.tex
└── ...
```

## Build
To locally build this, you will need to use LuaLaTeX as the document uses fontspec and microtype packages.

## Feedback
Any improvements is much appreciated!
