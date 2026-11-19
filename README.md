# Word Manager Pro

**Word Manager Pro** is a high-fidelity, privacy-first Microsoft Word (`.docx`) document workspace and productivity studio running 100% locally inside the web browser with zero server dependencies.

Official Production URL: **https://gksingh84.github.io/WordManager/**

---

## Key Features (Phase 1)

### 1. Document Viewer & Editor Studio
- **Dual-View Modes**:
  - **Page View (A4 Print Layout)**: True-to-life page margins (0.75 in), drop shadows, and page count estimator.
  - **Continuous Flow Mode**: Distraction-free, responsive editing canvas for phones, tablets, and laptops.
- **Rich Ribbon Toolbar**:
  - History: Undo (`Ctrl+Z`) and Redo (`Ctrl+Y`)
  - Typography: Font Family (Segoe UI, Calibri, Arial, Times New Roman, Georgia, Courier New, Verdana) and Font Sizes (8pt to 36pt)
  - Styling: Bold (`Ctrl+B`), Italic (`Ctrl+I`), Underline (`Ctrl+U`), Strikethrough, Subscript, Superscript
  - Color Engine: Custom Text Color and Highlight Marker palettes
  - Paragraph Alignment: Left, Center, Right, and Full Justify
  - Headings: Normal Text, Heading 1, Heading 2, Heading 3, and Blockquote
  - Lists: Bulleted Lists, Numbered Lists, and Task Checklists
  - Inserts: Interactive Tables (custom rows/cols, dynamic add/remove rows and columns, floating table toolbar, right-click context menu, and Tab navigation), Images with auto-resizing, Hyperlinks, Pre-styled Callout boxes, and Dividers
- **Open & Save**:
  - Open any existing `.docx` document using high-speed client-side parsing.
  - Save directly to genuine Microsoft Word `.docx` format.
  - 1-Click Export to PDF with print-ready vector styling.
- **Live Document Analytics**: Real-time word count, character count, estimated reading time, and page indicators.

---

### 2. Word Productivity Utilities
- **Merge Word Documents**: Drag-and-drop multiple `.docx` files to merge them into a single consolidated master document.
- **Deep Batch Find & Replace**: Search and replace across all paragraphs, headings, and table cells with Match Case and Whole Word options.
- **Watermark Engine**: Apply text watermarks (*CONFIDENTIAL*, *DRAFT*, *SAMPLE*, or custom text) with adjustable angle, opacity, and live preview.
- **Metadata Inspector & Cleaner**: Inspect author, last modified by, creation dates, and revision count; 1-click sanitize all metadata before sharing.
- **DOCX-to-PDF Conversion**: Instant client-side conversion without third-party server exposure.

---

### 3. Commercial Protection & Security
- **Domain Lock**: Bound to official verified domain `https://gksingh84.github.io/WordManager/`.
- **Anti-Cloning Shield**: Unauthorized copies automatically display a security lock screen.
- **Developer Offline Authorization**: Whitelisted local development environment for Windows user `3063429`.
- **Master Override PIN**: Encrypted SHA-256 PIN authentication (`346328`).
- **Keyboard Protection**: Disables `Ctrl+S`, `Ctrl+U`, `F12`, and dev tools inspection shortcuts.

---

### 4. File Structure
- `index.html`: Online production application powered by high-speed CDN assets.
- `Word_Manager_Offline.html`: 100% self-contained offline bundle with inlined vendor scripts for air-gapped environments.
- `vendor/`: Local copies of `jszip.min.js`, `mammoth.browser.min.js`, `docx-preview.min.js`, and `FileSaver.min.js`.
