# [ffmprovisr](http://amiaopensource.github.io/ffmprovisr)

Repository of useful FFmpeg command lines for archivists!

## What is this?

#### Project Objective

To facilitate better understanding of FFmpeg through collaborative sharing of useful scripts and detailed flag-level description of how each script works, so archivists can copy-paste and produce their own scripts, but also understand how and why they work.

## How do I see it?

The code is found in the gh-pages branch (the default primary branch). Readme is right here. You can see the site live on [GitHub pages](http://amiaopensource.github.io/ffmprovisr).

You can also install the latest [release](https://github.com/amiaopensource/ffmprovisr/releases) on your computer with the two commands:
```
brew tap amiaopensource/amiaos
brew install ffmprovisr
```
and then call it locally with the command:
```
ffmprovisr
```
This works currently under macOS, Linux and the Linux apps on Windows (Ubuntu and Debian tested). On classic Windows you can install the last [release](https://github.com/amiaopensource/ffmprovisr/releases) manually and the open `index.html` in a browser.

#### Parseable list of the commands

A list of all recipes in an easily parseable [ASCII text](recipes.txt) format is provided as well. It contains for each recipe its title and command in the following format:

```
# title of recipe 1
ffmpeg command 1
# title of recipe 2
ffmpeg command 2

...

# title of recipe n-1
ffmpeg command n-1
# title of recipe n
ffmpeg command n
```

The used [one-liner](scripts/get_recipe_list) is in the `scripts` folder.

## How do I contribute?

You are welcome to edit the codebase yourself, or just supply the information and ask it to be added to the site.

#### Edit codebase

To contribute to this project directly (and more quickly), clone this repository and create a new branch (`git checkout -b your-branch-name`) and add or modify a new block in `index.html`. Then [submit a pull request](https://github.com/amiaopensource/ffmprovisr/pulls) and the maintainers will review and integrate your code. There is a commented-out sample block available at the bottom of `index.html` that can be as a guideline for your command.

#### Make a request

If you are having trouble with coding it yourself or with GitHub, feel free to [submit an issue](https://github.com/amiaopensource/ffmprovisr/issues) with the kind of command you would like to see added to the site.

#### General help

If you want to help but don't have a new script to add, you can help us by testing out the scripts available, by refining or clarifying the documentation, or [creating an issue](https://github.com/amiaopensource/ffmprovisr/issues) for anything that sounds confusing and requires clarification.

## Code of Conduct

You can read our contributor code of conduct [here](https://github.com/amiaopensource/ffmprovisr/blob/gh-pages/code_of_conduct.md).

## Maintainers

[Ashley Blewer](https://github.com/ablwr), [Katherine Frances Nagels](https://github.com/kfrn), [Kieran O'Leary](https://github.com/kieranjol) and [Andrew Weaver](https://github.com/privatezero)

## Contributors
* Gathered using [octohatrack](https://github.com/LABHR/octohatrack)

*Code Contributors*:
ablwr (Ashley)  
bastibeckr (Basti Becker)  
b00giehead (Joanna White)  
bturkus  
dericed (Dave Rice)  
edsu (Ed Summers)  
jamessam (Jim Sam)  
jfarbowitz (Jonathan Farbowitz)  
kfrn (Katherine Frances Nagels)  
kgrons (Kathryn Gronsbell)  
kieranjol (Kieran O'Leary)  
llogan (Lou)  
mgiraldo (Mauricio Giraldo)  
pjotrek-b (Peter B.)  
privatezero (Andrew Weaver)  
retokromer (Reto Kromer)  
rfraimow  

*All Contributors*:
ablwr (Ashley)  
audiovisualopen  
bastibeckr (Basti Becker)  
b00giehead (Joanna White)  
brainwane (Sumana Harihareswara)  
bturkus  
dericed (Dave Rice)  
drodz11 (Dave Rodriguez)  
edsu (Ed Summers)  
EG-tech (Ethan Gates)  
federicomenaquintero (Federico Mena Quintero)  
Fizz24  
GregH18  
jamessam (Jim Sam)  
jfarbowitz (Jonathan Farbowitz)  
JonnyTech  
jronallo (Jason Ronallo)  
kellyhaydon (metacynic)  
kfrn (Katherine Frances Nagels)  
kgrons (Kathryn Gronsbell)  
kieranjol (Kieran O'Leary)  
llogan (Lou)  
mgiraldo (Mauricio Giraldo)  
mulvya  
nkrabben (Nick Krabbenhoeft)  
pjotrek-b (Peter B.)  
privatezero (Andrew Weaver)  
retokromer (Reto Kromer)  
rfraimow  
richardpl (Paul B Mahol)  
ross-spencer (Ross Spencer)  
todrobbins (Tod Robbins)  

Repo: amiaopensource/ffmprovisr  
Code Contributors: 17  
All Contributors: 32   
Last updated: 2019-02-11  

## AVHack Team

[Association of Moving Image Archivists & Digital Library Federation Hack Day 2015](http://wiki.curatecamp.org/index.php/Association_of_Moving_Image_Archivists_%26_Digital_Library_Federation_Hack_Day_2015)

[Ashley Blewer](https://github.com/ablwr), [Eddy Colloton](https://github.com/eddycolloton), Rebecca Dillmeier, [Jonathan Farbowitz](https://github.com/jfarbowitz), [Rebecca Fraimow](https://github.com/rfraimow), Samuel Gutterman, [Kelly Haydon](https://github.com/kellyhaydon), [Reto Kromer](https://github.com/retokromer), Nicole Martin, [Katherine Frances Nagels](https://github.com/kfrn), [Kieran O'Leary](https://github.com/kieranjol), Catriona Schlosser, [Ben Turkus](https://github.com/bturkus)

## Sister projects

[The Cable Bible](https://amiaopensource.github.io/cable-bible/): A Guide to Cables and Connectors Used for Audiovisual Tech  
[Script Ahoy](http://dd388.github.io/crals/): Community Resource for Archivists and Librarians Scripting  
[sourcecaster](https://datapraxis.github.io/sourcecaster/): helps you use the command line to work through common challenges that come up when working with digital primary sources.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png"></a><br>
This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" rel="dct:type">work</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://amiaopensource.github.io/ffmprovisr/" property="cc:attributionName" rel="cc:attributionURL">ffmprovisr</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br>
Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/amiaopensource/ffmprovisr" rel="dct:source">https://github.com/amiaopensource/ffmprovisr</a>.
