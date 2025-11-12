#!/bin/bash
# automation.sh — update the system and restart Apache

echo "Starting system update..."
sudo dnf -y update

echo "Restarting Apache web server..."
sudo systemctl restart httpd

echo "System updated and Apache restarted successfully."
