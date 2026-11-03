# Ankitha Betala — GitHub Portfolio

Responsive static portfolio built with HTML, CSS and vanilla JavaScript.

## Website structure
- `index.html` — profile, research interests, M.Tech thesis, skills and contact.
- `professional-experience.html` — dedicated professional-experience page with JWALA programme context, KAL RATO static-test data analysis and threaded motor bulkhead structural FEA.
- `assets/` — website images and technical plots.
- `resumes/` — downloadable CFD and FEA resumes.

## Preview locally
Open `index.html` in a browser, or run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Publish using GitHub Pages
1. Extract the ZIP archive.
2. Upload the contents of the `ankitha-portfolio` folder to the root of your existing GitHub repository, preserving the `assets/` and `resumes/` folders.
3. Commit and push the changes.
4. Check the published website and test the navigation, image loading and resume downloads.

## Before publishing
- Confirm that the threaded bulkhead stress contour and the RATO test plots/data are approved for public release by the relevant company/project authority. User-provided files are included in this working portfolio, but their presence here does not establish publication permission.
- Confirm that the original D1/D3 thrust plot's `thrust_kg` label represents kgf before changing its units or converting it to newtons. The supplied plot is currently displayed with its original axis labels.
- The additional thrust-time overview plot has unclear trace/axis metadata; its caption explicitly flags that limitation. Replace it with a correctly labelled source plot if available.
- The stress contour reports a maximum equivalent stress of 199.72 MPa and minimum of 0.12569 MPa at the displayed 1 s result time. Do not state a pass/fail result or factor of safety without material properties, loads, constraints, contact assumptions, mesh-convergence evidence and the applicable acceptance criterion.
- Public media links are included as external programme references; they do not imply authorship of the articles or prove individual technical contributions.
- Check both resume PDFs and replace them if either is not the final version.

## Design
The site uses a warm white/cream background, muted teal accents, restrained borders and responsive layouts.
