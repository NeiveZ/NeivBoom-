# Política de segurança do neivboom

## Relatar uma vulnerabilidade

Use **[Report a vulnerability](https://github.com/NeiveZ/neivboom/security/advisories/new)** na aba Security para iniciar um relato privado. Não publique detalhes de exploração, credenciais ou dados pessoais em issues.

O proprietário precisa habilitar o recurso de relato privado nas configurações do repositório. Se o botão não estiver disponível, abra uma issue pedindo somente um canal privado de contato, sem descrever a falha.

Informe a versão, Windows utilizado, comportamento observado, passos mínimos e impacto provável. Remova nomes de usuário, caminhos pessoais, IPs e identificadores de dispositivos de anexos que não sejam necessários. Nunca envie senhas, tokens ou dumps completos de memória.

## Versões e atendimento

O aplicativo está em testes. Correções serão direcionadas à versão mais recente publicada; versões antigas não têm manutenção garantida. Não há SLA de resposta ou auditoria independente anunciados. A ausência de relatos não garante ausência de vulnerabilidades.

## Privilégios e operações sensíveis

Use uma sessão normal sempre que possível. Captura ETW, drivers e alterações USB podem exigir elevação. Fechar processos pode perder trabalho não salvo; alterações de dispositivos e drivers podem interromper periféricos e exigir reinicialização. Faça backup antes dessas alterações.

Não desative antivírus, Controle Inteligente de Aplicativos ou outras proteções para executar o programa. A distribuição de testes ainda não possui assinatura digital de fornecedor confiável.

Baixe somente das [releases oficiais](https://github.com/NeiveZ/neivboom/releases). Um SHA-256 permite comparar arquivos com um valor confiável, mas não substitui assinatura do editor nem protege contra comprometimento simultâneo do pacote e do checksum.

## Escopo deste repositório

Este repositório distribui instaladores e documentação. Verificações feitas somente nele não cobrem automaticamente o código-fonte e suas dependências. Consulte também [Privacidade](PRIVACY.md) e [Suporte](SUPPORT.md).
