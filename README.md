GitLab server and runner setup

certificates for GitLab generated by  letsencrypt certbot https://certbot.eff.org/instructions?ws=nginx&os=ubuntufocal
openssl x509  -in /etc/letsencrypt/live/gitlab.tyi.name/fullchain.pem  -out /home/tyi/certs/gitlab.tyi.name.crt
cp /etc/letsencrypt/live/gitlab.tyi.name/privkey.pem /home/tyi/certs/gitlab.tyi.name.key

config file for gitlab-runner - config.toml

