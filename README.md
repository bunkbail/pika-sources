wget -qO - https://github.com/bunkbail/pika-sources/raw/refs/heads/main/pika-keyring.gpg.key  | sudo gpg --dearmor -vo /etc/apt/keyrings/pika-keyring.gpg.key

sudo wget -qO /etc/apt/sources.list.d/pika.sources https://github.com/bunkbail/pika-sources/raw/refs/heads/main/system.sources

sudo wget -qO /etc/apt/preference.d/0-pika-apt-settings https://github.com/bunkbail/pika-sources/raw/refs/heads/main/0-pika-apt-settings
