# OpenWRT Build for TP-Link Archer C6 v4 US

This repository allows you to build a pure OpenWRT stable firmware for TP-Link Archer C6 v4 US using GitHub Actions.

## Steps:

1. Create a new GitHub repository.
2. Upload the contents of this zip file into the repository.
3. Push to GitHub.
4. Go to the `Actions` tab in your repository.
5. Run the workflow `Build OpenWRT for Archer C6 v4 US`.
6. Wait for 10-15 minutes.
7. Download the generated firmware `.bin` file from the `Artifacts` section.
8. Flash the firmware via TP-Link Web UI (192.168.0.1).

**Note:**
- Always backup your stock firmware before flashing.
- Flashing firmware carries a risk of bricking your router.
