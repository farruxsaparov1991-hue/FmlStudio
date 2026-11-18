# FML STUDIO

Premium, responsive and multilingual website for FML STUDIO.

## Features

- Uzbek, Russian and Turkish interface with saved language preference.
- Responsive desktop, tablet and mobile layouts.
- Service overview: graphic design, video editing, logo design, advertising banners and creative content.
- Telegram project directory with working category filters and outbound channel links.
- About and contact sections, with in-page navigation.
- Order form validation and Telegram hand-off with a prefilled message.
- Existing studio logo asset retained.

## Project structure

- `index.html` — complete static website (HTML, CSS and JavaScript).
- `file_000000005470821080fa8e63f32ac374.jpg` — existing FML STUDIO logo asset.

The project intentionally stays framework-free; no build step or package installation is required.

## Run locally

Open `index.html` in a modern browser, or serve this directory with any static web server.

## Publish with GitHub Pages

1. Open the repository **Settings → Pages**.
2. Choose **Deploy from a branch**.
3. Select `main` and the `/ (root)` folder.
4. Save. GitHub Pages will publish the static site when deployment completes.

## Contact and order form

The order form validates the required fields and opens Telegram with a prefilled request addressed through the existing `@FmlStudioTv` link. The visitor must review and send the message in Telegram. This static site does not store or transmit orders to a private database.

If `@FmlStudioTv` is a broadcast-only channel rather than a chat-enabled Telegram account or bot, set the destination in the submit handler in `index.html` to the studio's actual order/chat username.

## Customization

- Edit the `translations` object in `index.html` to update Uzbek, Russian and Turkish copy.
- Update the `projects` array to add, remove or recategorize Telegram channels.
- Update the contact links and form destination if the studio's public contact account changes.
