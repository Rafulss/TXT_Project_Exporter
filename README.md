TXT Project Exporter
A lightweight, browser-based utility that combines project source files into clean, structured TXT exports. It runs entirely on the user's device and does not upload project files to a server.
Features
- Select a project directory or drag and drop it into the app.
- Reapply file and folder filters without selecting the directory again.
- Include all readable text files or limit the export to specified extensions.
- Enable or disable folder exclusions and edit the excluded folder names.
- Export one TXT file or split the export into multiple files.
- Keep each source file intact when splitting an export across multiple TXT files.
- View scanned, included, skipped, and output file counts.
Getting started
No build step, dependencies, or package installation are required.
1. Clone or download this repository.
2. Open index.html in a modern browser.
3. Select a project folder or drag and drop it into the drop area.
4. Configure the file filters and output format.
5. Download a single TXT file or export the configured set of TXT files.
For the best folder-selection and file-saving experience, use a recent version of Microsoft Edge or Google Chrome. Browsers that do not support the File System Access API will download exported files individually.
How filtering works
- All readable text files includes files with text content. Known binary formats and files detected as binary are skipped.
- Selected extensions only includes files matching the comma-separated extensions in the input field.
- Ignore selected folders can be switched on or off. Folder names are matched case-insensitively at any directory depth, excluding the selected project root.
- Changing any filter reprocesses the already selected file list. The project directory does not need to be selected again.
Privacy
File processing happens locally in the browser. The application does not send source files or file contents to an external server.
