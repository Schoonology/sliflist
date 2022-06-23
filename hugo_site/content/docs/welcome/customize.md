## How to customize the Sliflist without GitHub

No matter the reason for including—or omitting—a roll, there's bound to be reasons you want a favorite roll to be added to the wishlist. If that's you, here's how to customize the Sliflist:

1. Download the latest Sliflist:
   1. Open [`wishlist.txt`](https://raw.githubusercontent.com/rslifka/sliflist/main/wishlist.txt) in your browser.
   2. Click `File > Save` or press `Ctrl+S`/`Cmd+S` and save the file somewhere you'll remember.
2. Add your rolls
   1. Open that `wishlist.txt` file. If you don't know what to open it in, double-clicking it should open in either Notepad on Windows or TextEdit on a Mac.
   2. Add weapons (easy)
      1. Head to [Gunsmith](https://d2gunsmith.com/) and search for the weapon you want.
      2. Pick the perks you want to specify. Any columns left empty will show _all_ rolls of that column in your wishlist.
      3. Click the DIM Wishlist button under Extras (at the bottom). It doesn't show anything, but it works.
      4. Paste that on a new line of `wishlist.txt`. (I recommend doing so at the very top.) It'll look like this: `dimwishlist:item=1541131350`
      5. If you want any notes, add them on the end: `dimwishlist:item=1541131350#notes:Love this thing!`
      6. Save `wishlist.txt`.
   3. Adding armor is much more complicated. `TODO(schoon): Add these instructions anyway.`
   4. Add a title, notes, etc. (optional).
      1. At the very top of the wishlist, add some name for your new wishlist followed by an empty line or two.
      2. If you want to add additional notes about the wishlist in general, put them up here, too.
         - DIM will ignore these, but it'll make it clear to Future You what's going on.
3. Upload your custom wishlist to DIM:
   1. Head to [DIM's settings](https://app.destinyitemmanager.com/settings#wishlist).
   2. At the top of the Wish List section, click "Load Wish List Rolls".
   3. Select your wishlist file, and submit.
4. If you think your roll is great, [consider submitting it](https://www.sliflist.com/docs/welcome/roll_format/)!
