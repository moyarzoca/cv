# CV

This repository contains the LaTeX source for my curriculum vitae.

## Contents

- `cv_maoc.tex`: main CV source file
- `photo.jpg`: profile photo used in the header
- `cv_maoc.pdf`: compiled CV output
- `LICENSE`: MIT license

## Build

```bash
pdflatex cv_maoc.tex
```

## CV Structure

The CV is organized into these sections:

- Header with name, affiliation, contact links, and photo
- About me
- Employment
- Education
- Grants
- Fellowships
- Peer Review
- Teaching
- Organization of Events
- Publications
- Talks
- Participation in Schools and Conferences

## Notes

- The document uses a custom `cvblock` layout and helper commands defined in `cv_maoc.tex`.
- Generated LaTeX auxiliary files are ignored by Git.

## License

MIT
