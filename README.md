# QuoteHarbor

Keep the sentence. Keep its source.

Select a useful sentence, open QuoteHarbor, and save. The selection is previewed and its source is attached automatically. Notes and tags are optional; find the quote later in your local library.

## See it work

![Actual Chrome walkthrough](store/demo/walkthrough.gif)

[Video and steps](store/demo/README.md). Fictional demo data; FocusPet completion is accelerated and disclosed.

## Features

- Preview the selected passage when you open the extension.
- Save quote and source without writing a note or tags.
- Undo your last save in the popup.
- Search, edit and revisit quotes in the local library.
- Optional notes, tags, Markdown export and JSON backups.

## Limits

Stores up to 1,000 clips, with quotes and notes limited to 20,000 characters each. Capture works on permitted HTTP and HTTPS pages. Some pages, embedded frames, and browser PDF viewers do not allow capture; paste text manually when needed. QuoteHarbor does not highlight websites permanently, create verified academic citations, summarize with AI, or sync to a cloud. Existing MarginMemo notes migrate to the library on first open.

## Feedback

The help page links to honest Chrome Web Store reviews. An optional, dismissible notice appears after repeated successful use across at least one week; preferences stay on this device.

## Development

Load `extension/` unpacked in Chrome Developer mode. Run `npm test` and `npm run package`. There is no runtime dependency or build step.

## Privacy

Local data includes quotes, optional notes and tags, source titles and URLs, and timestamps. Opening the popup reads the current selection in the top page frame for a preview. The selection is saved only after you click Save.

`activeTab` temporarily accesses the current page after you invoke the extension. `scripting` reads selected text when the popup opens or when you click Refresh selected text. `storage` saves the library on this device. No background scanning occurs.

See [PRIVACY.md](PRIVACY.md). No accounts, ads or analytics.

## Product evidence

[Market analysis and validation plan](docs/market-analysis.md). Adoption remains unvalidated.

## Support and license

Use the repository issue tracker; remove private information. MIT.
