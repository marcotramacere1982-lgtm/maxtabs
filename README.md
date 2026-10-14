## Licence

MaxTabs is provided under the PolyForm Strict License 1.0.0.
See LICENSE for the complete terms.

The source is publicly visible, but this project is not open source.
Noncommercial use is permitted under the licence. Permission to
modify or redistribute the software is not granted by that licence.

Contact the maintainer to request additional permissions.

## User-created material

The software licence is not intended to impose restrictions on
music, tablature, or project data that users create themselves.
Third-party musical material remains subject to its own rights.



Even though the app can ultimately be packaged as one self-contained HTML file, developing it as separate files is much easier to maintain. Later, you can bundle or inline everything into a single index.html if you want a portable file.

Folder/file	Purpose
index.html	App shell: fretboard, tab area, transport controls, chord panel
styles/	All CSS, keeping UI styling separate from behaviour
scripts/	JavaScript modules, each with one clear responsibility
data/	Editable JSON for tunings, instruments, and chord shapes
docs/	Durable project memory for you and any AI assistant
tests/	Manual test checklists now; automated tests later
examples/	Sample songs for testing import/export and playback
.vscode/	Workspace-specific editor settings
