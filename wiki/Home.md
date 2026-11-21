# SigmaOS-goneovim

SigmaOS integration component for **Goneovim**.

## Commands

```bash
sigmaos-goneovim install   # install package + deploy defaults
sigmaos-goneovim deploy    # copy config templates to $HOME
sigmaos-goneovim status    # binary/package/config report
sigmaos-goneovim reset     # remove deployed config
sigmaos-goneovim open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
