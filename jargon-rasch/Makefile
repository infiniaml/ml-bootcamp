#pandoc -r markdown+fenced_divs -t beamer -i bootcamp-jargon.md -o slides.pdf -V theme=Dresden -V classoption=notes -V beameroption="show notes on second screen=bottom"

bootcamp-jargon.pdf: bootcamp-jargon.md img/*
	pandoc -r markdown+fenced_divs -t beamer -i bootcamp-jargon.md -o bootcamp-jargon.pdf -V theme=Dresden 
#pandoc -t revealjs -s -o myslides.html bootcamp-jargon.md -V revealjs-url=http://lab.hakim.se/reveal-js
#pandoc -t revealjs -s -o myslides.html bootcamp-jargon.md -V revealjs-url=./reveal.js

