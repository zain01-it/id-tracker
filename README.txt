ID Printing Tracker — vertical keypad layout

ID printing layout:
- All controls are arranged vertically in one full-width section.
- Enter the number of IDs using its own on-screen numeric keypad (0–9, Clear, Backspace).
- Select how many IDs fit on ONE paper sheet using the 1–6 keypad.
- Every ID batch consumes exactly ONE paper sheet, regardless of the ID quantity or selected fit number.
- Every ID still consumes one lamination sheet.

Xerox layout:
- The Xerox controls are arranged vertically in one full-width section.
- Enter the number of paper sheets used with its own on-screen numeric keypad.
- Xerox income is ₱5 per sheet. Completing a Xerox entry deducts the same number of paper sheets from stock.
- Each Xerox entry can be undone; undo reverses its income and paper usage.

Profit accounting:
- ID printing income = IDs × configured selling price.
- Xerox income = Xerox sheets × ₱5.
- Lamination expense = lamination sheets used × configured lamination cost.
- Net profit = ID printing income + Xerox income − lamination expense.
- Paper is quantity-only inventory; it does not create a peso expense.

Deploy:
1. Extract this ZIP on Android.
2. Upload/replace index.html in the root of the GitHub repository connected to your existing Vercel project.
3. Commit to the production branch, then wait for Vercel's automatic deployment.

Records and settings are saved in this browser/device using localStorage. Deploying an updated site does not automatically move localStorage data to another browser or device.


Xerox quantity now starts blank. Enter a quantity with the keypad; the preview remains blank until a valid quantity is entered. After completing a Xerox job, the quantity resets to blank.
