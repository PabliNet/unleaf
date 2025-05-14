# unleaf

Split a PDF file into individual pages using `pdfseparate`.  
Divide un archivo PDF en páginas individuales usando `pdfseparate`.

## 🧩 Features / Características

- ✅ Splits each page of a PDF into a separate file  
- ✅ Optional custom output name (without path)  
- ✅ Detects and reports errors (missing tools, invalid PDFs, etc.)  
- ✅ Multilingual: English and Spanish messages  

---

## 📦 Requirements / Requisitos

- `pdfinfo`  
- `pdfseparate`  

These are included in the `poppler-utils` package.  
Estos comandos están disponibles en el paquete `poppler-utils`.

---

## 📥 Installation / Instalación

Copy the script to a directory in your `$PATH`, e.g.:

```sh
sudo install -m755 unleaf /usr/local/bin/
