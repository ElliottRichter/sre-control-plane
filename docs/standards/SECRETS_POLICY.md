# Secrets Policy

Never commit:

- passwords
- API keys
- kubeconfig
- terraform secrets
- SSH private keys
- certificates

Use:

example.env
sanitized.yaml
template.tfvars

Redact:

192.168.x.x
tokens
emails
credentials
