# KCC Loan AutoFILL — GitHub Pages upload pack

Upload **everything in this folder** to the **root** of your GitHub repo  
(`jugaad-online/KCC_Loan_AutoFILL`), then enable GitHub Pages (branch: `main` / `master`, folder: `/`).

## Live app

https://jugaad-online.github.io/KCC_Loan_AutoFILL/MailMerge_Field_Names.html

Or open the site root (redirects to the app):  
https://jugaad-online.github.io/KCC_Loan_AutoFILL/

## App files (required for github.io preview)

| File | Why |
|------|-----|
| `MailMerge_Field_Names.html` | Main app |
| `forms_preview_content.js` | **Required for Live Form Preview** |
| `index.html` | Opens the app from the Pages home URL |
| `KCC_Demo_50_Samples.xlsx` | 50 sample KCC rows — **Upload Excel (ALL)** |
| `MailMerge_DIY_Fields.xlsx` | Excel template with correct headers |
| `README.md` | This file |

## Word form templates (your docs)

Tagged mail-merge `.docx` forms (download from the repo anytime):

- `A1.docx`
- `A21A.docx`
- `A3.docx`
- `A47.docx`
- `Agri revised A-1.docx`
- `KCC Sanction Letter.docx`
- `PSLD-1.docx`
- `PSVR Agri.docx`
- `S14 - Acknowledgement of Debt & Security..docx`

These are for reference / local exact generation. The online app preview uses `forms_preview_content.js` (built from these forms).

## How to upload

1. Open repo: https://github.com/jugaad-online/KCC_Loan_AutoFILL  
2. Upload or push **all files from this `GITHUB` folder** to the **repo root** (not a subfolder).  
3. Wait 1–2 minutes for Pages to refresh.  
4. Hard-refresh the live URL (Ctrl+F5).

## Check that preview works

DevTools → Network: `forms_preview_content.js` → **200 OK** (not 404).

## Notes

- Excel / ZIP features need internet (SheetJS + JSZip CDNs).
- Exact `.docx` fill (`Generate_Exact_Docs.bat`) stays on your PC in the main `FORMS` folder.
