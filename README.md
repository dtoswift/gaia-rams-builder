# Gaia RAMS Builder

A single-page tool for creating site-specific RAMS as Word documents from Gaia's content library.

## Use

Open the published page, choose the work, tick the site conditions, add the site details and click **Create Word document**. The file downloads to your computer.

## Status

Content library **v0.1-draft**, assembled from 26 existing Gaia RAMS templates and pending migration review. Every document produced is marked *DRAFT – for approval before issue* and must be approved by the Operations Manager before it goes to site.

## How it works

Everything runs in the browser. The content library is embedded in `index.html`; the Word file is built with [docx](https://www.npmjs.com/package/docx) 9.6.1, loaded from jsDelivr. Nothing typed into the form is sent anywhere.

## Updating content

Replace `index.html` with the new version and commit. Record the library version and what changed in the commit message.
