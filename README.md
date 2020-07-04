# README

This is the README for the Balisage 2020 presentation by Ari Nordström.


## Installing

1. Clone the presentation Git repository from `https://github.com/sgmlguru/balisage2020-pipelined-xslt.git` to somewhere nice (`git clone https://github.com/sgmlguru/balisage2020-pipelined-xslt.git`).
2. Change the working directory to your newly cloned `balisage2020-pipelined-xslt` directory.
3. Do `git clone https://github.com/hakimel/reveal.js.git`.
4. Do `cd reveal.js/`.
5. Run `npm install`.
6. Replace `index.html` with a symbolic link to `../index.html`: `ln -s ../index.html index.html`.
7. Add a symbolic link to `../img/`: `ln -s ../img/ img`.


## Running

1. Run `npm start` in `balisage2020-pipelined-xslt/reveal.js/`.
2. The presentation should open in your default browser.