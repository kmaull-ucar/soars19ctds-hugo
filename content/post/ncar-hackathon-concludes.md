+++
title = "NCAR/CGD Hackathon Concludes"
description = "So many resources ..."
date = 2019-06-08T00:00:00Z
math = true

tags = [
    "python",
    "research",
    "scientific computing"
]

categories = [
    "python",
    "research",
    "resources"
]
+++

Last Wednesday June 5, was the last day of a 3-day hackathon hosted by the [Climate & Global Dynamics (CGD) Group](https://www.cgd.ucar.edu) at NCAR and I wanted to share a few things that you should really know about with regarding why Python will be so important in your scientific research and computational future.

### THE LANDSCAPE AND HISTORY OF NCL AND FORTRAN
A large proportion of the modeling and computation code written here at NCAR has been developed in [NCL (NCAR Command Language)](https://www.ncl.ucar.edu) and FORTRAN.  NCL was developed several decades ago (in the mid-90s) to support data processing and visualization of scientific data (primarily, but not restricted to, atmospheric and geoscience).  It supports a number of common file and data formats, and facilitates the presentation of common plots, visualizations and graphics used in presenting scientific results.  

FORTRAN (FORmula TRANslation) is a language that was originally developed at the early epoch of digital computers in 1957 &mdash; the same year USSR successfully launched and deployed the Earth's first artificial satellite, Sputnik I!  Needless to say, FORTRAN has undergone **many, many** changes since its first version, and the longevity of the language is a clear testament to its importance, but many hundreds of languages have been developed since then, advantaging themselves of the corresponding changes in programming language paradigms and computer architectures (e.g. supercomputer technologies) over the years.  While it is true FORTRAN is still the language of choice for benchmarking high performance scientific computing, it is nonetheless showing its age now that the first fifth of the 21st century is rear view mirror ... 

FORTRAN and NCL provide the foundation for many millions of lines of code behind the most important weather and climate models used by NCAR and others today, yet they have now reached the point of a profound pivot.

### THANK YOU NCL, HELLO PYTHON

If you take a look at the [NCL webpage](https://www.ncl.ucar.edu) you'll notice the following disclaimer:

> Important: NCAR has made the decision to adopt Python as the scripting language platform of choice for future development of analysis and visualization tools. Please read this open letter to NCL users to understand what kind of impact this will have on the future of NCL.

This notice is one reason CGD put on the Hackathon.  It is a not-so-subtle reminder that there are shifts underway &mdash; indeed, you can read the full rationale in ["Important letter regarding the future of NCL"](https://www.ncl.ucar.edu/open_letter_to_ncl_users.shtml).

Python (the language) is not exactly new as some may assume since it is [so popular today](https://pypl.github.io/PYPL.html) &mdash; in fact, as of June 2019, [Python ranked #1 in the Worldwide PYPL index](https://pypl.github.io/PYPL.html) with 28.08% global share well ahead of Java which had a 20.51% global share.  The language was conceived by Guido Van Rossum in 1989, was _officially released_ in 1991, and Python v1.0 was released 1992.  Python was initially developed as a general purpose programming language borrowing concepts from [C](https://en.wikibooks.org/wiki/C_Programming), [C++](http://www.cplusplus.com/), [Modula-3](http://modula3.org/about_m3/), [Perl](https://www.perl.org/), [Shell Script](https://www.shellscript.sh/) and [ABC](https://homepages.cwi.nl/~steven/abc/).  The syntax of Python is designed for readability and thus convoluted and complex to read code are counter to both the design philosophy of the languange and community norms.  In a significant way, this simplicity has contributed to the success and popularity of the language and allows beginners to  become productive very rapidly.  Not only can they learn to write code quickly, the learning curve is reduced because the can **read** the code of others right away. Three precepts from the 18 contained in [The Zen of Python](https://www.python.org/dev/peps/pep-0020/) sum up what I (and perhaps many others) enjoy most about the language:

>  Simple is better than complex.

> Complex is better than complicated.

> In the face of ambiguity, refuse the temptation to guess.

> If the implementation is hard to explain, it's a bad idea.

Orient yourself to the entire Zen of Python as it will help you navigate the community philosophy as well as the motivations behind many language constructs.

Which brings us to Python in the atmospheric and geosciences.

Python has seen at meteoric rise and and rapid acceptance into geosciences within the last decade, but Python had been used in scientific programming since the early 2000s ([Van Andel, 1999](http://styx.livinglogic.de/~walter/www.python.org-xhtmlified/workshops/2000-01/proceedings/papers/van_andel/perp.pdf); [Beazley, 2000](http://adsabs.harvard.edu/abs/2000ASPC..216...49B); [Silva, et al, 2001](10.1109/SIBGRAPI.2001.963108); [Hinson, 2002](http://manual.freeshell.org/py-Scientific/manual.pdf); [S&aacute;enz, et al. 2002](https://doi.org/10.1016/S0098-3004(01)00086-3)).  The importance of software and computation has always been crucial to atmospheric modeling and weather forecasting, but in the last decade and a half especially, the pressure for skills in scientific software has increased dramatically as the volume and complexity of computational problems have become more demanding.  It is not surprising that the inviting "Pythonic" design philosophy and language constructs make implementing algorithms and writing scientific code so much easier.

The development of Python utilities for geoscience has exploded and many things are now very easy and accessible for atmospheric and geoscience analyses, starting with reading and manipulating common file formats like NetCDF, HDF, GRIB and good old ASCII text files (which vast observational datasets have been stored in).

### FROM HERE, WHERE ...
The hackathon drew a nice sized crowd (there were at least 40 people present during the session I was able to attend) and there were many questions, ranging from how to make the transition to Python _least_ painful, to how to support the community that has broad and varied skills and needs &mdash; from Pythonistas to  Python newbies.  Everyone acknowledges that the transition moving forward will not be easy, but it is important that there is enough support for everyone, no matter where they are.

The transition to Python is moving forward and it will be easier    for some than others, but in the realm of computing, change is the denominator in every advance and whether we like it or not, we have to adapt and learn new tools and skills that help make us more productive at what we do.  Do so allows our work to remain relevant and valuable to the communities who use it. 

### RESOURCES YOU CAN USE

The hackathon is over, but some useful resources that were created as a result of it (for participants _and_ everyone) which I think are well worth bookmarking:

* [the Hackathon's main site](https://ncar-hackathons.github.io/)
* Guide to [Scientific Computing in Python](https://ncar-hackathons.github.io/scientific-computing/intro) with a very nice introduction to Numpy and Xarray!
* and if you're just getting started with Python, check out their [The Python General Guide](https://ncar-hackathons.github.io/python-general/intro).

If you've been hesitant about jumping into Python, now's not the time to be shy!  No matter where you are in your understanding of the language and how it might fit into your work, there's no better time than _now_ to get started.
