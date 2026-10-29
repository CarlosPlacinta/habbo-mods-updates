# Habbo Mods

Mods para o Habbo (cliente do Habbo Launcher, botão **PLAY HABBO**): mais níveis de zoom, menu redondo no clique
direito, inventário e guarda-roupa redimensionáveis com visual novo, comandos como `:shadow` e o painel `:painel`,
e o Habbo em 64 bits.

## Instalar

1. Baixe **HabboModsSetup.exe** da [versão mais recente](../../releases/latest).
2. Abra o arquivo. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações** e depois
   em **Executar assim mesmo** (o instalador não tem assinatura paga da Microsoft).
3. Clique em **Instalar** e espere alguns minutos. Se o Habbo estiver aberto, feche quando pedir.
4. Abra o Habbo pelo Habbo Launcher, em **PLAY HABBO**.

Quando o Habbo atualizar, o Habbo Mods reinstala os mods sozinho assim que você fechar o Habbo. Novas versões dos
mods também chegam sozinhas.

Para remover: Configurações do Windows → Aplicativos → **Habbo Mods** → Desinstalar. O Habbo volta a ser como veio.

## About this repository

Releases only. Each release has the setup program, a bundle (the installer program, the mod sources it compiles on
the user's own PC, and the 64-bit Adobe AIR runtime), and `latest.json`, which installed copies check for updates.
`latest.json` is signed with an Ed25519 key that only the publisher holds, and the bundle and the tools it downloads
(Temurin Java 8 from Adoptium, JPEXS FFDec) are pinned by SHA-256, so installed copies refuse anything else.
No Habbo game files are distributed here: each PC patches its own.

Not affiliated with Sulake or Habbo.
