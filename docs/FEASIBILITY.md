# Ghost in the Shell release candidate

Alex accepted the corrected Windows development build on September 5, 2026. The runtime preserves ExitCriticalSection registers used by the opening movie. This closes the reported video/input hold.

The source recipe preserves the accepted game configuration and seed bytes.
Portable paths, setup wizard support, executable naming, and explicit retail BIOS policy are release changes.
Framework provenance is recorded in [the project manifest](../project-manifest.toml) and `psxrecomp/RELEASE-SOURCE.json`.
The four-platform workflow builds setup hosts and generators without retail inputs.
First-run setup, gameplay, save/load, and native Linux/macOS acceptance remain separate checks.
No quality graduation or complete-game claim is made here.
