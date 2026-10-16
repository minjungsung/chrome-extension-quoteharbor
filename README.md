# MarginMemo

A thought belongs with its page.

Keep private notes for the pages you visit. Search your page notes, export a backup, and keep your research in one place.

## Development

Open `chrome://extensions`, enable Developer mode, choose **Load unpacked**, and select `extension/`. No build or package dependencies are needed.

Run `npm test` for logic tests and `npm run package` to validate and create a clean ZIP in `dist/`.

## Privacy

See [PRIVACY.md](PRIVACY.md) for stored data and permission explanations. No accounts, analytics, ads, or developer servers.

## Support

Report bugs through this repository's issue tracker. Include reproducible steps and the extension version, with private information removed.

## License

MIT.

## Features and limits

MarginMemo keeps your thoughts next to the pages that inspired them. Save a note for the current page, then search your note library when you need it again.

FEATURES
- One private note per web page, up to 20,000 characters each.
- A searchable library for up to 1,000 page notes.
- Edit saved notes and reopen their source pages.
- Export a JSON backup and import it without overwriting existing page notes.
- No accounts, cloud sync, ads, or analytics.

Open a web page, click MarginMemo, write your note, and choose Save note. Notes match the page URL excluding its fragment; distinct query strings count as distinct pages. Changes are saved explicitly with the Save controls. Notes are not inserted into websites and page content is not read.

PRIVACY
Notes, page URLs, titles, and update times stay in local extension storage. Exported backups may contain sensitive notes or private URLs; keep them somewhere you trust. Uninstalling removes local notes.
