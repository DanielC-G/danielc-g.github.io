# Daniel Cerqueda-García — Researcher profile

Bilingual academic website focused on insect pest microbiota, ecology and evolution.

Intended public address: https://danielc-g.github.io/

## Site files

- `index.html`: the approved English/Spanish profile, including its images, CSS, JavaScript and 63 publication entries.
- `.nojekyll`: disables Jekyll processing for the static website.

The initial publication pull request must remain a draft until the complete `index.html` has been uploaded and checked. Do not merge a preparation-only pull request.

## Publication through a pull request

1. Upload the supplied `index.html` to the root of the existing `publicar-perfil-investigador` branch. Commit to that branch, not directly to `main`.
2. Check the existing pull request: `publicar-perfil-investigador` → `main`. Confirm that `index.html` is included and that the profile displays correctly.
3. Mark the pull request ready for review, then merge it into `main`.
4. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. Check the Pages deployment in **Actions**, then open the public address.

An open pull request does not by itself publish the website.

## Content and privacy

The approved profile retains English/Spanish switching, the original banner and portrait, and 63 publication entries. Its current research scope focuses on insect pests and their microbiota, ecology and evolution; historical publication titles are preserved.

The contact address is displayed in obfuscated form without a `mailto:` link. ResearchGate is retained; the GitHub social-profile link is omitted. Obfuscation is not a guarantee against automated harvesting.

Do not add private CVs, administrative documents, personal identifiers, credentials or access tokens to this public repository.

## Technical note

The supplied `index.html` preserves the approved page body and embedded images. Manrope and Newsreader are requested through Google Fonts instead of embedding font binaries; the existing fallback font stacks remain available.

## Official documentation

- [Configuring a GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Adding a file to a repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
