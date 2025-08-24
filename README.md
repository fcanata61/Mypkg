# mypkg

`mypkg` é um **gerenciador de pacotes source-based** simples, estável e 100% funcional, escrito em **POSIX sh**, inspirado em sistemas de ports e gerenciadores como `portage`, `pacman` e `makepkg`.  

Ele permite baixar, compilar, instalar e gerenciar pacotes de forma automática, incluindo resolução de dependências, patches, logs e mais.

---

## Recursos

- Build, install, remove, upgrade, sync
- Resolução de dependências recursiva
- World rebuild (recompila todo o sistema)
- Download via `curl`, `wget` e `git`
- Suporte a patches e hooks
- Logs detalhados
- SHA256 e verificação de integridade
- Clean de diretório de trabalho
- Destdir e fakeroot
- Flags coloridas, spinner, help
