Stack:
- kitty

- greetd
instalation:
sudo dnf install greetd greetd-tuigreet

sudo systemctl disable sddm
sudo systemctl stop sddm

sudo systemctl enable greetd
sudo chown root:root /etc/greetd/config.toml
