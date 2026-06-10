# 🚀 Saguinus

A lightweight writing environment for standalone documents and focused content creation.

Built for speed, simplicity, and direct interaction with your writing.

---

## ✨ Core Capabilities

### 🧠 Distraction-Free Editing
A minimal writing surface designed to reduce friction and keep attention on content creation.

- Responsive and lightweight interface  
- Smooth scrolling and live rendering  
- Optimized for uninterrupted writing flow  

---

### 📄 Independent Documents
Each file exists as a self-contained unit.

There are no enforced structures, hierarchies, or workflows — you decide how to organize your work.

---

## 🖼️ Preview

![Saguinus Preview](./assets/welcome.PNG)

---

## ⚠️ Testing Phase Notice

Saguinus is currently in active development and should be considered a testing-stage product.

Core functionality is in place, but several systems are still evolving and may behave inconsistently.

### Known issues (v0.1.0)

- Editor layout may shift slightly during rendering cycles  
- Tables and code blocks are not yet visually polished  
- Newly created pages may load with a short delay  
- Differences may appear between editor view and exported preview  
- Images are currently restricted to preview rendering only  
- Font customization controls are not yet functional  

---

### Known Issues – v0.2.0

This release includes several improvements and partial fixes from v0.1.0, along with new functionality and ongoing stability work. Some previously identified issues have been resolved, while others remain in progress.

#### Improvements and Fixed Issues

* Images now supported in editorImage rendering has been extended from preview-only to include editor support. Consistency between editor and export is still being refined.

* Font customization partially resolvedFont customization controls now function correctly within the editor. However, export support for font styling remains incomplete.

* Reduced layout inconsistencies (partial fix)Some editor layout shifting issues observed in v0.1.0 have been improved, though edge cases may still occur under certain window conditions.
---

#### Remaining Known Issues

* Incorrect PDF export filenameExported PDF files still default to the in-app document name instead of the user-defined export dialog name.

* Unstable export font stylingFont styling in exported documents is not stable. Font size adjustments are currently not applied consistently.

* Code block duplication on pasteCopy-pasting code blocks may result in an additional unwanted wrapper or header being created.

* Missing or incomplete formatting featuresThe following formatting features are not yet implemented or are only partially supported:

  *  Links
  * Mathematical expressions

  * Strikethrough text

  * Checkbox lists

* Editor responsive layout issueThe editor may shrink when the application window is not maximized and can initialize with incorrect dimensions in some cases.

* Inline formatting serialization issueInline formatting is not consistently converted to Markdown. Instead, it may be stored or rendered as rich text.
---
