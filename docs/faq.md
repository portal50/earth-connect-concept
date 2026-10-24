# FAQ

### Is there a working SDK?
No. This repository is for concept validation and early developer feedback.

### Is this a one-line integration?
Not today. A future lightweight script might register a world or display a limited guest area, but full 3D integration would require engine-specific adapters or scene hooks.

### Could any object enter any scene?
No. Rendering, animation, collisions, gravity and actions vary by engine and host world. An adapter would declare supported capabilities, reject unknowns and provide safe fallback behavior.

### What makes this different from importing a model?
The research hypothesis adds persistent identity, provenance, authorized state and host-controlled access across independently operated spaces, not simply copying a 3D file.

### Can a host refuse pets or gifts?
Yes, that is a core proposed rule. The host should decide what enters, where, and which actions are possible.

### Who controls Mimi's state?
A single designated authority should validate any persistent state change. A remote display must not silently change the original authoritative state.

### Does this require moving to Earth Online hosting?
The intended concept does not. Creators would keep their own domain, engine and hosting. This independence has not yet been proven with a public SDK.

### Is this a published standard?
No. Existing standards and products must be evaluated before introducing new protocol requirements.

### Can I test it today?
Not as an SDK. You can give feedback or offer an existing project for a future limited pilot.

### How can I participate?
Open an issue using the integration-interest or use-case template. Please do not post credentials, confidential business data or sensitive personal information.
