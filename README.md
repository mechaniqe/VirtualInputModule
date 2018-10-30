# VirtualInputModule
A modified StandaloneInputModule that allows UI events to be driven by a virtual mouse cursor. Does not handle cursor movement. [Original version](https://github.com/AmyDentata/VirtualInputModule) written for **Unity 5.3.4f1** was shared by **AmyDentata**.

**Note:** The virtual mouse cursor must be a canvas object.

## Setup
- Replace StandaloneInputModule with VirtualInputModule on the EventSystem game object.
- Assign a canvas object to m_VirtualCursor.
- Assign the canvas camera to m_CanvasCamera.

Tested in **Unity 2018.1.9**
