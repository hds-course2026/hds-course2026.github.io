# High-Dimensional Statistics course website

This project is a High-Dimensional Statistics adaptation of the MkDocs Material structure used by the `deeprl2026/deeprl2026.github.io` course repository.

## Local preview

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
mkdocs serve
```

Then open `http://127.0.0.1:8000`.

## Deploy

Push to `main` or `master`. The GitHub Actions workflow publishes the site with `mkdocs gh-deploy`.

## Course-data notes

- The 30-session schedule and assessment dates come from `HDS_Syllabus.xlsx`.
- The first two Aparat recordings are linked on the Lectures and Schedule pages.
- The main textbook and course purpose follow the previous High-Dimensional Statistics offering.
- The new TA roster was **not present** in the supplied spreadsheet, so the old roster has intentionally not been copied. Update `docs/staff.md` when the new team names/contact details are available.
- The original Deep RL Google Analytics property was intentionally removed so HDS traffic is not attributed to the old site.
