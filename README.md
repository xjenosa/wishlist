# wishlist

**wwishe, wishlists in Chrome's side panel.**

You type a list the way you type in Notepad. A line is an item and the price
that ends it, a title gathers the lines under it, and every title and the list
add themselves up. wwishe has no server and no account, and keeps your lists in
Chrome's own storage.

This repository hands out the built extension until wwishe is on the Chrome Web
Store. It holds no source code.

## Install

1. Download this repository with **Code**, then **Download ZIP**, and unzip it
   somewhere it can stay.
2. Open `chrome://extensions` and turn on **Developer mode**, at the top right.
3. Click **Load unpacked** and choose the `wwishe` folder inside it.
4. Click the puzzle piece in Chrome's toolbar and pin wwishe. Its icon, or
   Alt+Shift+S, opens and closes the panel.

**Keep the folder where it is.** Chrome knows an extension loaded this way by
its folder, so wwishe loaded from another folder starts with no lists. To
update, Export each list first, put the new files in the same folder, and click
the reload arrow on wwishe in `chrome://extensions`. When wwishe is on the
Chrome Web Store, Export each list here and Import it there.

## Using it

- Type a line and end it with a price and its mark, `Lamp $25`. The price goes
  to its column and the totals follow. A number with no mark stays part of the
  name.
- `# ` at the start of a line makes it a title.
- The circle marks an item owned, and the star puts it on the shortlist. The
  filter shows All, Shortlist or Owned, each with its total, and the sort orders
  the lines under each title without changing your order.
- The list's name opens its menu, with your other lists, New list, Import,
  Export and Recently deleted, where a deleted list waits 30 days. Each list has
  its own currency, set beside its name there.
- Export saves a list as a text file, a line an item, `# ` before a title and
  `*` before an item owned, which Notepad opens and Import reads back.

## Keys

| Key | Does |
|---|---|
| Alt+Shift+S | opens and closes the panel |
| Enter | splits a line, or starts a new one |
| Ctrl+Z, Ctrl+Y | undo and redo |
| Ctrl+C, Ctrl+X, Ctrl+V | copy, cut and paste lines, each star going with its line |
| Ctrl+click, Ctrl+Shift+click | pick whole lines |
| Del | deletes the lines picked |
| Alt+Shift+Up, Alt+Shift+Down | move a line, or a title with its lines |
| Ctrl+F | finds a word or a price in the list |
| Shift+F10 | opens the right-click menu where the caret is |
| Tab | goes from a line's circle to the line and its star |

## Privacy

wwishe sends nothing over the internet. Chrome sync carries your lists to your
other computers only when your Chrome syncs extensions. The whole policy is
[PRIVACY.md](PRIVACY.md).

## Licence

wwishe is free to use, under the Terms in its Settings. Its code is douwble's,
all rights reserved, as [LICENSE](LICENSE) says. It ships the typeface Inter,
under the SIL Open Font License, whose text is `wwishe/fonts/OFL.txt`.

Questions go to wwishe@douwble.com.
