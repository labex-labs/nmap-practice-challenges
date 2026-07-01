# Desafios práticos de Nmap

## Idiomas

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇷🇺 [Русский](README_ru.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<img width="128px" src="https://file.labex.io/upload/u/1991/1aTkiz91H4KB.png">
</div>

Aprenda Nmap, uma ferramenta de código aberto poderosa para exploração de rede e auditoria de segurança. Este roteiro de aprendizagem oferece cursos Nmap abrangentes, projetados para iniciantes em cibersegurança. Siga um caminho estruturado para dominar a varredura de rede, descoberta de portas e avaliação de vulnerabilidades. Através de tutoriais práticos (não em vídeo) e exercícios práticos em um ambiente de teste de varredura de rede dedicado, você ganhará experiência real no uso do Nmap para mapear redes e identificar riscos de segurança.

Explore até 29 desafios focados de Nmap no LabEx. Cada desafio abre em um ambiente interativo para você praticar habilidades específicas.

|   Índice | Nome                                                                                                                                  | Habilidades                       | Dificuldade   | Prática                                                                                           |
|----------|---------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------|---------------|---------------------------------------------------------------------------------------------------|
|       01 | [Enumeração Rsync e Sincronização Anônima](https://labex.io/pt/labs/linux-rsync-enumeration-and-anonymous-sync-596723)                | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/linux-rsync-enumeration-and-anonymous-sync-596723)     |
|       02 | [Revisar Descobertas de Serviço Incertas](https://labex.io/pt/labs/review-uncertain-service-findings-705352)                          | Revisão de falsos positivos       | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/review-uncertain-service-findings-705352)              |
|       03 | [Passar Argumentos Necessários para Scripts NSE](https://labex.io/pt/labs/pass-required-nse-script-arguments-705351)                  | Argumentos de script              | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/pass-required-nse-script-arguments-705351)             |
|       04 | [Comparar resultados do Nmap antes e depois](https://labex.io/pt/labs/compare-before-and-after-nmap-results-705350)                   | Comparação de resultados          | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/compare-before-and-after-nmap-results-705350)          |
|       05 | [Acesso Inicial com Metasploit](https://labex.io/pt/labs/metasploit-driven-initial-access-657543)                                     | Redirecionamento de saída         | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/metasploit-driven-initial-access-657543)               |
|       06 | [Revisão de Priorização de Vulnerabilidades](https://labex.io/pt/labs/vulnerability-prioritization-review-657539)                     | Gerenciamento de vulnerabilidades | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/vulnerability-prioritization-review-657539)            |
|       07 | [Mapeamento de Rede Corporativa](https://labex.io/pt/labs/enterprise-network-mapping-657537)                                          | Especificação de destino          | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/enterprise-network-mapping-657537)                     |
|       08 | [Desafio de Invasão de Rede Interna](https://labex.io/pt/labs/linux-internal-network-breach-challenge-656176)                         | Segurança de rede                 | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/linux-internal-network-breach-challenge-656176)        |
|       09 | [Comprometimento de Primeira Sangria (First Blood)](https://labex.io/pt/labs/linux-first-blood-compromise-656167)                     | Superfície de Ataque              | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/linux-first-blood-compromise-656167)                   |
|       10 | [Desafio de Enumeração de Alvo](https://labex.io/pt/labs/linux-target-enumeration-challenge-656139)                                   | Redirecionamento de saída         | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/linux-target-enumeration-challenge-656139)             |
|       11 | [Desafio de Mapeamento de Rede](https://labex.io/pt/labs/linux-network-mapping-challenge-656134)                                      | Especificação de destino          | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/linux-network-mapping-challenge-656134)                |
|       12 | [Missão de Reconhecimento Passivo](https://labex.io/pt/labs/linux-passive-reconnaissance-mission-656130)                              | Redirecionamento de saída         | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/linux-passive-reconnaissance-mission-656130)           |
|       13 | [Ataque de Força Bruta em Telnet e Credenciais Fracas](https://labex.io/pt/labs/linux-telnet-brute-force-and-weak-credentials-596726) | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/linux-telnet-brute-force-and-weak-credentials-596726)  |
|       14 | [Enumeração SSH e Acesso Baseado em Chave](https://labex.io/pt/labs/linux-ssh-enumeration-and-key-based-access-596725)                | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/linux-ssh-enumeration-and-key-based-access-596725)     |
|       15 | [Enumeração SMB e Acesso de Convidado](https://labex.io/pt/labs/linux-smb-enumeration-and-guest-access-596724)                        | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/linux-smb-enumeration-and-guest-access-596724)         |
|       16 | [Instalar o Nmap e Realizar Varredura de Portas](https://labex.io/pt/labs/nmap-install-nmap-and-perform-port-scanning-415923)         | Ciclo de vida do pacote           | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/nmap-install-nmap-and-perform-port-scanning-415923)    |
|       17 | [Enumeração de RDP e Acesso com Senha Fraca](https://labex.io/pt/labs/linux-rdp-enumeration-and-weak-password-access-596722)          | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/linux-rdp-enumeration-and-weak-password-access-596722) |
|       18 | [Enumeração HTTP e Travessia de Diretório](https://labex.io/pt/labs/linux-http-enumeration-and-directory-traversal-596721)            | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/linux-http-enumeration-and-directory-traversal-596721) |
|       19 | [Enumeração FTP e Acesso Anônimo](https://labex.io/pt/labs/linux-ftp-enumeration-and-anonymous-access-596695)                         | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/linux-ftp-enumeration-and-anonymous-access-596695)     |
|       20 | [Varredura com Nmap e Acesso via Telnet](https://labex.io/pt/labs/nmap-nmap-scanning-and-telnet-access-596683)                        | Superfície de Ataque              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/nmap-nmap-scanning-and-telnet-access-596683)           |
|       21 | [Escanear Portas de Rede com Nmap](https://labex.io/pt/labs/kali-scan-network-ports-with-nmap-552280)                                 | Especificação de destino          | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/kali-scan-network-ports-with-nmap-552280)              |
|       22 | [Identificar a Versão do Servidor Linux](https://labex.io/pt/labs/nmap-identify-linux-server-version-548747)                          | Detecção de sistema operacional   | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/nmap-identify-linux-server-version-548747)             |
|       23 | [Encontrar Porta UDP Aberta](https://labex.io/pt/labs/nmap-find-open-udp-port-548746)                                                 | Varreduras UDP                    | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/nmap-find-open-udp-port-548746)                        |
|       24 | [Descubra a Porta Secreta](https://labex.io/pt/labs/nmap-uncover-the-secret-port-548724)                                              | Saída de texto                    | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/nmap-uncover-the-secret-port-548724)                   |
|       25 | [Escanear Alvos a Partir de um Arquivo](https://labex.io/pt/labs/nmap-scan-target-from-file-548715)                                   | Especificação de destino          | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/nmap-scan-target-from-file-548715)                     |
|       26 | [Salvar a saída do Nmap em XML](https://labex.io/pt/labs/nmap-save-nmap-output-to-xml-548705)                                         | Saída Estruturada                 | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/nmap-save-nmap-output-to-xml-548705)                   |
|       27 | [Encontrar Porta Aberta no Servidor Luna](https://labex.io/pt/labs/nmap-find-open-port-on-luna-server-548697)                         | Seleção de porta                  | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/nmap-find-open-port-on-luna-server-548697)             |
|       28 | [Verificar a Versão do Serviço Localmente](https://labex.io/pt/labs/nmap-verify-service-version-locally-548693)                       | Detecção de sistema operacional   | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/nmap-verify-service-version-locally-548693)            |
|       29 | [Varredura de Sub-rede com Nmap](https://labex.io/pt/labs/nmap-scanning-subnet-with-nmap-415954)                                      | Especificação de destino          | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/nmap-scanning-subnet-with-nmap-415954)                 |

[Ver todos os desafios](https://labex.io/pt/learn/nmap).

## Mais

- 🔗 [Saiba mais sobre Nmap no LabEx](https://labex.io/pt/learn/nmap)
- 🔗 [Explore mais projetos de programação](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [Explore cursos de programação](https://github.com/labex-labs/awesome-programming-courses)

