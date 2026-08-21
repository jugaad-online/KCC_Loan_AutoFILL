# KCC Loan AutoFILL — GitHub Pages upload pack

Upload **everything in this folder** to the **root** of your GitHub repo  
(`jugaad-online/KCC_Loan_AutoFILL`), then enable GitHub Pages (branch: `main` / `master`, folder: `/`).

## Live app

https://jugaad-online.github.io/KCC_Loan_AutoFILL/MailMerge_Field_Names.html

## App files (required for preview)

| File | Why |
|------|-----|
| `MailMerge_Field_Names.html` | Main app — choose **HTML** or **Word (.docx)** generate |
| `forms_preview_content.js` | **Required for Live Form Preview** |
| `index.html` | Redirects Pages home → app |
| `KCC_Demo_50_Samples.xlsx` | Demo Excel (Upload Excel ALL) |
| `MailMerge_DIY_Fields.xlsx` | Excel template |
| `README.md` | This file |

## Word form templates (required for Word generate mode)

- `A1.docx`, `A21A.docx`, `A3.docx`, `A47.docx`
- `Agri revised A-1.docx`, `KCC Sanction Letter.docx`
- `PSLD-1.docx`, `PSVR Agri.docx`
- `S14 - Acknowledgement of Debt & Security..docx`

On github.io these load automatically. If you open HTML as a local `file://` page, use **Load Word templates** in the app.

## Generate modes

| Mode | Output |
|------|--------|
| **HTML (.doc)** | Filled preview HTML (opens in Word) |
| **Word templates (.docx)** | Fills `<<FieldName>>` in your real bank forms |

## Upload steps

1. Push/upload **all files in this folder** to the **repo root**.
2. Wait for Pages to refresh; hard-refresh (Ctrl+F5).
3. Confirm `forms_preview_content.js` returns **200** (not 404).
