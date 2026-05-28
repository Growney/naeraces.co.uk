# naeraces.co.uk

## GitHub Actions Setup

Create a ssh keypair with `ssh-keygen`, which GitHub Actions will use to SSH to the VMs.

- Add the private key to GitHub in `Settings` - `Secrets and variables` - `Actions` - new secret called `SSH_PRIVATE_KEY`.
- Add the public key to the VMs with `echo "the key" >> ~/.ssh/authorized_keys`.
