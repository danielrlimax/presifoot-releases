# Presifoot Installer Exit Codes

The Presifoot Windows installer is built with Inno Setup.

| Exit code | Meaning |
|---|---|
| 0 | Installation completed successfully. |
| 1 | The installer failed to initialize. |
| 2 | The user cancelled before installation started. |
| 3 | A fatal error occurred while preparing the installation. |
| 4 | A fatal error occurred during installation. |
| 5 | The user cancelled or aborted during installation. |
| 7 | The installer determined that installation could not proceed. |
| 8 | Installation could not proceed and Windows must be restarted. |

Any other non-zero code should be treated as an installation failure.

## Support

Please report installation problems through the Issues section of this repository.
