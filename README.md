# flashexp
Flash editor
Flash Editor Studio — fully self-contained, single file. Here's what's implemented:

**Loading** — animated progress bar with staged messages before app reveals.

**File Menu** — New, Open (drag & drop / browse), Save as .swf, Save code .as, Save as .fla (JSON).

**Edit Menu** — 20+ actions: Undo, Redo, Cut, Copy, Paste, Delete, Select All, Deselect, Find, Duplicate, Group, Ungroup, Lock/Unlock, Merge, Flatten, Align, Distribute, Arrange, Free Transform, Convert to Symbol, Break Apart, Swap Symbol, Edit Symbol.

**Effects Menu** — Hue, Invert, Saturation, Grayscale, Stretch, Wave Warp, RGB Split, Twirl, Kaleidoscope — all pixel-level applied to the canvas via ImageData.

**ActionScript Editor** — open/close/continue editing, Run, Syntax Check, Insert Template, Clear; the editor panel is a live modal textarea.

**Color Picker** — HSL gradient canvas, hue slider, RGB inputs, hex input, 32-swatch palette, targets stroke/fill/stage-bg.

**All 40 Tools** — grid modal with every tool icon.

**Preferences → 20 Settings** — 5 sections (General, Editor, Canvas, Shortcuts, Export) with toggles, numbers, text, selects.

**Preferences → 20 Errors** — error console with type filter (errors/warnings/info), live list, clear button.

**Preferences → 30 Languages** — full grid with flags, active selection, apply.

**Plugins** — manage list with on/off toggles, search, Create Plugin form (name, author, version, type, JS code entry), register into list.

**Drawing Canvas** — rect, ellipse, line, pencil/brush (freehand), text, fill tool; undo/redo stack.

**Timeline** — layers, frame cells, play/stop/step controls, seekable frames.
