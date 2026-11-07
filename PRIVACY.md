# Privacidade no neivboom

O aplicativo consulta hardware, sensores, processos, jogos instalados, dispositivos, drivers e informações de rede para apresentar diagnósticos. Nomes de processos, caminhos, contas locais e identificadores de hardware podem ser dados pessoais.

No escopo do código revisado, não foi identificado envio automático de telemetria a um servidor do projeto. Isso não equivale a uma auditoria independente. O programa utiliza conexões necessárias a recursos solicitados: GitHub para atualizações, Windows Update para drivers e DNS/ICMP para testes de rede. Launchers têm suas próprias políticas.

Configurações, histórico e logs podem permanecer no perfil local do Windows, em pastas do neivboom ou PainelDesempenho dentro de LocalAppData. Relatórios HTML/JSON são gravados no destino escolhido pelo usuário. A desinstalação pode deixar dados locais; remova-os manualmente se desejar, após salvar o que precisar.

Revise relatórios, capturas e logs antes de compartilhar. Remova nomes de usuário, caminhos pessoais, IPs, números de série e outros dados desnecessários. Não envie dumps de memória, senhas ou tokens.

Relatos públicos e anexos no GitHub ficam visíveis a outras pessoas. Para vulnerabilidades, siga [SECURITY.md](SECURITY.md).
