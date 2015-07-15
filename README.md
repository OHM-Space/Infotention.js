# Infotention.js
A set of javascript libraries that implement Howard Rheingold's ideas on Infotention and Mind Amplifiers. The system should be similar to Yahoo pipes and allow users to easily create new "pipe" scripts. Yahoo Pipes is stopping its service this year and this new system could be used by many of their users. 

From Mindful Infotention: Dashboards, Radars, Filters - http://blog.sfgate.com/rheingold/2009/09/01/mindful-infotention-dashboards-radars-filters/

'Infotention is a word I came up with to describe the psycho-social-techno skill/tools we all need to find our way online today, a mind-machine combination of brain-powered attention skills with computer-powered information filters. The inside and outside of infotention work best together'

I would like our deisn philosophy to follow Douglas Englebart's H/LAM-T system described in his seminal paper "AUGMENTING HUMAN INTELLECT: A CONCEPTUAL FRAMEWORK".

From "AUGMENTING HUMAN INTELLECT: A CONCEPTUAL FRAMEWORK" - http://www.dougengelbart.org/pubs/augment-3906.html

'By "augmenting human intellect" we mean increasing the capability of a man to approach a complex problem situation, to gain comprehension to suit his particular needs, and to derive solutions to problems. Increased capability in this respect is taken to mean a mixture of the following: more-rapid comprehension, better comprehension, the possibility of gaining a useful degree of comprehension in a situation that previously was too complex, speedier solutions, better solutions, and the possibility of finding solutions to problems that before seemed insoluble. And by "complex situations" we include the professional problems of diplomats, executives, social scientists, life scientists, physical scientists, attorneys, designers--whether the problem situation exists for twenty minutes or twenty years. We do not speak of isolated clever tricks that help in particular situations. We refer to a way of life in an integrated domain where hunches, cut-and-try, intangibles, and the human "feel for a situation" usefully co-exist with powerful concepts, streamlined terminology and notation, sophisticated methods, and high-powered electronic aids.'

The FIRST STAGE of development is to create a Yahoo Pipes style interface and an API for wrapping javascript libraries such that they are usable with the "Dataflow" style of programming, similar to Pure Data (PD). The individual scripts could communicate by consuming and emmiting structured text in the form of JSON objects.

From wikipedia article - https://en.wikipedia.org/wiki/Dataflow_programming

'In computer programming, dataflow programming is a programming paradigm that models a program as a directed graph of the data flowing between operations, thus implementing dataflow principles and architecture. Dataflow programming languages share some features of functional languages, and were generally developed in order to bring some functional concepts to a language more suitable for numeric processing. Some authors use the term Datastream instead of Dataflow to avoid confusion with Dataflow Computing or Dataflow architecture, based on an indeterministic machine paradigm.'

The SECOND STAGE is to recreate the functionality of Yahoo Pipes and to create modules that are specifically targeting the different aspects of Infortention and Mind Amplification following the H-LAM/T philosophy.


References:
* Yahoo Pipes Video - https://www.youtube.com/watch?v=8XSm8ZyxMrU
* JSON - http://json.org/
* Infortention Mindmap - http://cmapspublic3.ihmc.us/rid=1GGG55974-H3VQRB-J1D/Infotention%20Filters.cmap
* Mind Amplifier Book - http://blog.ted.com/new-ted-book-mind-amplifier/
* NetSmart Book - http://www.amazon.com/Net-Smart-How-Thrive-Online-ebook/dp/B007D5UP9G
* Online clases with Howard! Check out Mini-Courses - http://www.rheingold.com/university/
* Yahoo Pipes - http://pipes.yahoo.com/pipes/
* POSIX - https://en.wikipedia.org/wiki/C_POSIX_library

Note: Since Yahoo Pipes is shutting down. I'll attempt to post PDFs of the documentation soon
Note: Howard Rheingold is not involved in this project. I took a couple online classes with Howard as the intructor. If we build something that works, I'm sure he'll be very excited and willing to share the project with other developers in his "personal learning network".
