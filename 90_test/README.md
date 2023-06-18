# Vagrant with Dockerfile

- In progress

## Prerequisites

```bash
sudo groupadd docker
sudo usermod -aG docker $USER
```

You will have to log out and log back in for the changes to take effect.

If you want to activate the changes to groups in your current session, run:

```bash
newgrp docker
```

## References

<https://developer.hashicorp.com/vagrant/docs/providers/docker/basics>
<https://dev.to/mattdark/using-docker-as-provider-for-vagrant-10me>
