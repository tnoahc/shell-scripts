## Interactive Linux Server Hardening
This script addresses tasks such as user management, SSH configuration, firewall setup, and more.

### How to Use the Script
Save the script as `harden_server.sh`

```bash
# Make it executable
chmod +x harden_server.sh
# Run the script as root
sudo ./harden_server.sh
```

Follow the interactive prompts to harden your Linux server.

### Key Features

- **System Updates**: Keeps your packages up-to-date.
- **User Management**: Adds a new user with sudo privileges.
- **SSH Hardening**: Disables root login and password-based authentication.
- **Firewall Setup**: Configures UFW to allow only SSH by default.
- **Intrusion Prevention**: Installs and configures Fail2Ban.
- **Unused Services**: Disables unnecessary services like `cups`.
- **Memory Security**: Secures shared memory against exploits.
- **Auto Updates**: Configures unattended-upgrades for automatic updates.
