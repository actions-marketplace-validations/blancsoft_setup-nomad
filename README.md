# Nomad GitHub Action

This GitHub Action sets up Hashicorp Nomad CLI by adding a step to your workflow.

```yaml
  - name: Hashicorp Nomad
    uses: blancsoft/setup-nomad@v1
```

## Defining version and shasum

Set which Nomad version to use. `sha256sum` is optional.

```yaml
  - name: Hashicorp Nomad
    uses: blancsoft/setup-nomad@v1
    with:
      version: 1.6.2
      sha256sum: f6f879a359a667a6b1ca4366abd8383d89118dabd0d28af5bbc4721685ff17b8
```
