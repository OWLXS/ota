# OWLXS OTA manifests

Manifestos JSON lidos pelo app Updater (`packages/apps/Updater`) da Axion,
schema `org.lineageos.updater.misc.Utils.parseJsonUpdate()`.

Estrutura: `<VARIANT>/<device>.json` (ex: `GMS/lamu.json`), igual à
convenção usada pelo `AxionAOSP/official_devices` — só que aqui só tem o
`lamu`/`lamulite`, que não é device oficial da Axion.

Os ZIPs em si NÃO ficam aqui — vivem como assets de Release em
`OWLXS/android_device_motorola_lamu` (ou repo equivalente), o `url` de
cada entrada do JSON aponta pra lá.

Publicado manualmente, só depois de uma build ser testada no aparelho —
nunca automático a cada build com sucesso.
