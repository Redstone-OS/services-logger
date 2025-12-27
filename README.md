# logger

Serviço de registros e diário do sistema (Journal).

## O que ele deve ser?
O repositório central de mensagens de log. Ele substitui o antigo `logd` com uma estrutura mais robusta e organizada.

## O que precisa fazer?
- [ ] **Coleta Centralizada**: Receber logs de todos os outros serviços via IPC.
- [ ] **Armazenamento**: Salvar logs em memória (circular) e no disco (persistente).
- [ ] **Filtragem**: Permitir busca e filtragem por serviço, nível de erro ou data.
- [ ] **Debug em Tempo Real**: Permitir que administradores "assistam" aos logs enquanto acontecem.
- [ ] **Rotação**: Garantir que os logs não ocupem todo o espaço em disco.
