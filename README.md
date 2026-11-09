# gdm-startup-patch
A simple fix for managing gdm fs permission requirements and optional gsettings commands. Tested on systemd (262.1-1-arch) and GDM (51.1).

# Instructions
```bash
sudo systemctl enable set_gui_permissions@root.service
sudo systemctl enable set_gui_settings@yourusernamegoeshere.service
sudo systemctl daemon-reload
```
