# docker-LaTeX

**Purpose:** Allow building LaTeX documents using a container (i.e. without installing LaTeX locally).

For example, run the following

```bash
docker run --rm -v "$PWD":/prj drorata/docker-latex dror_atariah.tex
```

from a directory where you have a `.tex` file that you'd like to build.
