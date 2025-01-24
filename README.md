# preCICE talk at the von Karman Institute for Fluid Dynamics

- Title: Coupling OpenFOAM with external codes via preCICE
- Speaker: Gerasimos Chourdakis, University of Stuttgart
- Authors: Gerasimos Chourdakis, Jun Chen, + [more](https://www.precice.org/about/)
- Event: [VKI OpenFOAM seminar](https://github.com/ofcourse-VKI/ofseminar/tree/master) - [announcement](https://events.vki.ac.be/index.php/von-karman-institute-events-and-lecture-series/free-openfoam-seminar-january-2025-gerasimos-chourdakis), online (Belgium)
- Date: January 24, 2025

[Start the presentation](https://makish.github.io/vki-training/) - [Get the PDF](https://github.com/MakisH/vki-training/blob/master/slides.pdf)

This training session is an excerpt of the content typically discussed in the [preCICE Workshops](https://precice.org/precice-workshop.html). Do you want more training for you, your university, or your company? Consider [supporting preCICE](https://precice.org/community-support-precice).

## Build

Follow the instructions on [reveal.js](https://revealjs.com/installation/), or just install Node.js 10.0.0 or later and do:

```bash
npm install
npm start
```

and go to [localhost:8000](http://localhost:8000/) to see the slides.

## Convert to PDF

See section "[Export to PDF](https://revealjs.com/pdf-export/)" in the reveal.js documentation.

[Decktape](https://github.com/astefanutti/decktape) does a marvelous job converting this presentation to PDF. Get the Docker image (see Decktape README) and run (for localhost):

```bash
docker run --rm -t --net=host -v "$(pwd)":/slides astefanutti/decktape generic --key=" " -p 2000 -s 1920x1440 http://localhost:8000 slides.pdf
```

## License & more

- Based on the material of a related training session at the [OpenFOAM Workshop 2024](https://github.com/MakisH/ofw19-training)
- License: [CreativeCommons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
- Based on [reveal.js](https://github.com/hakimel/reveal.js). Template based on the "White" template by Hakim El Hattab.
- The University of Stuttgart logo is part of the corporate identity of the University of Stuttgart.
