<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/airlock-org/.github/main/profile/assets/airlock-wordmark-thin-red-dark.svg">
    <img alt="AirlockOS" src="https://raw.githubusercontent.com/airlock-org/.github/main/profile/assets/airlock-wordmark-thin-red-light.svg" height="64">
  </picture>
</p>

**A Xen-based desktop OS built with Rust, Qubes, and Nix.**

AirlockOS combines Qubes VM isolation with a shared GNOME desktop. Rust services
and machine configuration define how the system works, while Nix builds
reproducible system generations for whole-machine rollback.

- Whole-system Nix rollback, including dom0 and VMs.
- Shared global Nix store with read-only VM closure views.
- One GNOME desktop for applications running in separate VMs.

[Website](https://airlockos.org/) · [Documentation](https://airlockos.org/docs/) · [Source](https://github.com/airlockos-org/airlockos)

AirlockOS is under active development. Qubes OS security equivalence has not been
established.
