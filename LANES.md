# Lanes into Canva

Operating notes for the people who push files into this repo. Moved out of `PLAYBOOK.md` on 2 September 2026 so the staff playbook carries only what a carousel session needs.

## Lanes into Canva, and which one to pick

The connector never accepts a local file. This note is for whoever runs the repo from a machine with a shell, and a staff session building a carousel through the connector never needs it. When the thing to deliver already exists on disk, a finished PowerPoint or an image, there are two ways in and they reach different accounts.

**Upload from disk through the browser. The default.** In Chrome, open `Projects > Uploads`, click `Add new`, and let the menu build its file inputs. Upload straight to `input[type=file]` with the browser tool's file-upload action. Never click "Upload files" itself, which opens a native picker no automation can answer. Canva converts an uploaded `.pptx` into an editable design, fonts and point sizes intact. Nothing is published anywhere, and the design arrives in whichever account Chrome is signed into. This is the only route to a personal account.

**Public URL through this repo.** Push the file here, then call `import-design-from-url` on its `raw.githubusercontent.com` address. Use this lane for a headless run, or where the asset is public already. Know this before choosing it. The file becomes readable by anyone the moment it lands, and the connector is bound to the Yoga Australia account, so every design this lane makes arrives in the YA estate. Personal or studio work does not belong there.

Both lanes were proven end to end on 30 and 31 August 2026 with the same two-page 1080×1920 deck.

## Rebuilding a rendered tile as an editable deck

A design that began as an HTML render becomes an editable Canva design by way of a PowerPoint with real text boxes. Measure, since re-deriving fails. Render the source HTML, read each block's `getBoundingClientRect` and its computed type facts, screenshot the background with the text layer hidden, then build the deck on those numbers.

The trap that decides whether it works is line height. A CSS `line-height` written into the deck as a multiple is read against the font's own leading, so every block grows and collides with the one below it. Set exact points instead, `Pt(css_px * 0.75)`. PowerPoint also places the first baseline higher than the browser under exact spacing, so measure the offset against the approved render and nudge the box.

