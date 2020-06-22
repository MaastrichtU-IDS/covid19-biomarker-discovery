# Covid-19 Biomarker Discovery

A project about biomarker discovery for COVID-19 research. 

### Literature annotator

Automatically annotate scientific literature using the [BioPortal Annotator](https://bioportal.bioontology.org/annotator).

```bash
cd literature-annotator
```

Start a JupyterLab locally from the `literature-annotator` folder:

```bash
docker run --rm -it -p 8888:8888 -v $(pwd):/notebooks -e PASSWORD="<your_secret>" umids/jupyterlab:latest
```

