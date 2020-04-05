JavaScript for Shiny Users
================

### rstudio::conf 2020

by Garrick Aden-Buie

-----

:spiral_calendar: January 27 and 28, 2020  
:alarm_clock:     09:00 - 17:00  
:hotel:           Continental Ballroom Room 6 (Ballroom Level)  
:writing_hand:    [rstd.io/conf](http://rstd.io/conf)

-----

### Workshop Links

- :house: [Workshop Website - js4shiny.com](https://www.js4shiny.com)
- :package: [pkg.js4shiny.com](https://pkg.js4shiny.com)
- :speech_balloon: [chat.js4shiny.com](https://chat.js4shiny.com)
- :raising_hand_woman: [help.js4shiny.com](https://help.js4shiny.com)
- :card_file_box: [repo.js4shiny.com](https://repo.js4shiny.com)
- :postbox: [RStudio Community thread](https://community.rstudio.com/t/javascript-for-shiny-users-workshop-rstudio-conf-2020/49095)

-----

## Overview

Shiny gives users a powerful toolkit to create interactive web applications. As a result, Shiny users are also web developers! Inevitably, an intermediate Shiny user will want to create a visualization or user interface that isn't available in the `shiny` package. Fortunately, we can use the building blocks of the web -- JavaScript, HTML, and CSS -- to extend Shiny's capabilities and create engaging Shiny apps.

This two-day, hands-on workshop will introduce Shiny users to JavaScript, the ubiquitous scripting language that powers the modern web. We will explore JavaScript's syntax and will discover its functional programming style to be refreshingly familiar to tidyverse R users. We will learn how to use JavaScript to manipulate HTML and how Shiny uses JavaScript to communicate between the browser and Shiny server. Together, we will build an `htmlwidget` and as we learn how to incorporate our own or packaged JavaScript code into Shiny apps and RMarkdown documents, and how to simultaneously manage JavaScript and R dependencies.

## Learning objectives

Attendees will learn basic JavaScript and how to use JavaScript to manipulate HTML and CSS in interactive webpages. We will explore how to use JavaScript effectively in Shiny apps using htmlwidgets and htmltools. We delve into how Shiny uses JavaScript to build engaging Shiny apps.

## Is this course for me?

This workshop is for the Shiny user who boldly waded into the *Customizing Shiny* section of shiny.rstudio.com/articles and quickly wished they had more experience with JavaScript. This user recognizes the benefits of learning JavaScript, but she is overwhelmed by the sheer number of packages, tutorials, and StackOverflow questions that exist in the world. The goal of this workshop is to meet the Shiny user where they are now to learn the best parts of JavaScript that will provide the most value and facilitate learning and exploration after the workshop.

## Prework

:woman_technologist: Please follow the instructions at https://js4shiny.com/resources/setup/ to get started.

We will spend most of our time in this workshop in RStudio and a web browser. [RStudio Desktop][rstudio-desktop] is preferred because we will occasionally need to run commands like `npm` in your computer's terminal or console.

I recommend the [Firefox], [Firefox Developer Edition][firefox-dev], or [Chrome] browsers and will use Firefox during the workshop.

[rstudio-desktop]: https://rstudio.com/products/rstudio/
[firefox]: https://www.mozilla.org/en-US/firefox/new/
[firefox-dev]: https://www.mozilla.org/en-US/firefox/developer/
[chrome]: https://www.google.com/chrome/


## Schedule

We have a lot planned for our time together,
so the _topics listed below provide a general overview_ and may change.
The **times are certain** and fixed
(unless the rstudio::conf schedule changes).

### Monday, January 27

| Time          |                        | Activity                |
| :------------ | ---------------------- | :---------------------- |
| 09:00 - 10:30 | :clapper:              | Web Dev 101             |
| 10:30 - 11:00 | :coffee:               | *Coffee break*          |
| 11:00 - 12:30 | :nail_care:            | Interactivity and Style |
| 12:30 - 13:30 | :bento:                | *Lunch break*           |
| 13:30 - 15:00 | :zap:                  | JavaScript              |
| 15:00 - 15:30 | :coffee:               | *Coffee break*          |
| 15:30 - 17:00 | :globe_with_meridians: | R for Web Dev           |

### Tuesday, January 28

| Time          |                  | Activity                    |
| :------------ | ---------------- | :-------------------------- |
| 09:00 - 10:30 | :package:        | htmlwidgets                 |
| 10:30 - 11:00 | :coffee:         | *Coffee break*              |
| 11:00 - 12:30 | :phone:          | Communicating with Shiny    |
| 12:30 - 13:30 | :bento:          | *Lunch break*               |
| 13:30 - 15:00 | :dancing_women:  | Extending Shiny             |
| 15:00 - 15:30 | :coffee:         | *Coffee break*              |
| 15:30 - 17:00 | :woman_juggling: | Building Awesome Shiny Apps |

## Instructor

[Garrick Aden-Buie][garrick] is an
[RStudio certified trainer][rstudio-trainer] and a data scientist at
the [Moffitt Cancer Center][moffitt] in the
[Collaborative Data Services Core][moffitt-cdsc] where he uses and trains
others to use R, Shiny, and the tools of data science to accelerate research
towards the prevention and cure of cancer.

[garrick]: https://www.garrickadenbuie.com
[moffitt]: https://moffitt.org
[moffitt-cdsc]: https://moffitt.org/research-science/shared-resources/collaborative-data-services/
[rstudio-trainer]: https://education.rstudio.com/trainers

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
