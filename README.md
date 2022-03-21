# XLIFF best practices -- OmegaT sample project

This is an OmegaT team project you can open in OmegaT, meant to exemplify some do's and don'ts when we create XLIFF files out of HTML or XML content as native formats.

## Contents

The project's structure is as follows:

```
.
├── dictionary
├── glossary
├── omegat
├── original
│   ├── entities.html
│   ├── markup_custom.xml
│   ├── markup_inline.svg
│   ├── markup_input.html
│   ├── markup_span.html
│   └── segmen_para.html
├── README.md
├── source
│   ├── 01_haram
│   │   ├── entities.html.xlf
│   │   ├── markup_custom.xml.xlf
│   │   ├── markup_inline.svg.xlf
│   │   ├── markup_input.html.xlf
│   │   ├── markup_span.html.xlf
│   │   └── segmen_para.html.xlf
│   ├── 02_halal_xlf1
│   │   ├── entities.html.xlf
│   │   ├── markup_custom.xml.xlf
│   │   ├── markup_inline.svg.xlf
│   │   ├── markup_input.html.xlf
│   │   ├── markup_span.html.xlf
│   │   └── segmen_para.html.xlf
│   └── 02_halal_xlf2
│       ├── entities.html.xlf
│       ├── markup_custom.xml.xlf
│       ├── markup_inline.svg.xlf
│       ├── markup_input.html.xlf
│       ├── markup_span.html.xlf
│       └── segmen_para.html.xlf
├── target
└── tm

```

The `original` folder contains the original files in XML, SVG and HTML, whereas the `source` folder contains the corresponding XLIFF files in three different flavours: the "haram" version shows what shouldn't be done, the "halal" versions show what should be done instead, in both XLIFF v1.2 and v2.0 (no difference between those two versions with regards to display).

## How to use it

You may filter in the file list in OmegaT by one particular file, e.g. `markup_para`. If you type the name of one file, you will see the three flavours of that file: haram, halal v1.2 and halal 2.0. Alternatively you can simply click on the file you want to display in the translation editor. 

Recommended way to go through the project: after you examine one "haram" XLIFF file, open the "halal" version of the same file and observe the difference. You may want to go back and forth between the two or download it twice in two different local locations so that it's possible to open the two files (haram and haral) side by side.ddfadñlfkj

## Credentials

To download the project in OmegaT as a team project, you must have a Github account and have set a personal token that allows access to public repositories.
