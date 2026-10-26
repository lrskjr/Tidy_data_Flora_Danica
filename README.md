# Tidy data i regneark. Flora Danica

Workshoppen er en Jupyter Book. Deltagerne arbejder i Excel. Teksten er skrevet i Markdown.

## Byg bogen

Kræver Anaconda. Kør kommandoerne i mappen med *myst.yml*.

```
pip install "jupyter-book>=2"
jupyter book build --html
```

HTML-filerne ligger i *_build/html*. Siderne bruger stier fra roden af den mappe, så de åbnes med en lokal server:

```
python -m http.server -d _build/html 8000
```

Åbn http://localhost:8000
