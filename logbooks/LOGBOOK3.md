# CVE 2021-34473

## Identificação

- Vulnerabilidade no Microsoft Exchange Server.
- Permite aos atacantes ultrapassar autenticação, fazer-se passar por user arbitrário e escrever ficheiro, com o fim de executar código remotamente.
- Rede como vetor de ataque.
- Sem necessidade de acesso a privilégios ou interação do utilizador.

## Catalogação

#### Report: 
* O bug foi anunciado pela Microsoft em 13/07/2021.
* O problema resulta da falta de devida validação do URI antes de aceder a recursos.
* O bug-bounty tem valor em _200.000$_ e nível de gravidade _Muito Alto_.

## Exploit

* As explorações do PowerShell são um exemplo de malware sem arquivo, sobre o qual escrevemos de maneira mais geral em outros lugares.
* O Microsoft Security Response Center fornece um website para encontrar detalhes sobre CVEs com updates de segurança ou mitigações.
* Metasploit.
* Microsoft's Sysmon

## Ataques

* Em dezembro de 2021, explorou-se vulnerabilidades do PowerShell através do Microsoft Exchange Server para aceder à rede do departamento polícia norte-americano.
* Também nesse mês, foram exploradas essas vulnerabilidades com objetivo de ganhar acesso a rede da companhia regional de transporte norte-americano.
* Em fevereiro 2022, com vulnerabilidades na Log4j, aplicação VMware Horizon, acedeu-se à rede do governo norte-americano para operações de "crypto-mining".
* Em fevereiro 2022, a Guarda Revolucionária Iraniana alavancou um servidor de agências avaliadoras para exfiltrar dados da rede de companhia.

## Referências

* https://msrc.microsoft.com/update-guide/vulnerability/CVE-2021-34473
* https://packetstormsecurity.com/files/163895/Microsoft-Exchange-ProxyShell-Remote-Code-Execution.html
* https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-34473
* https://www.zerodayinitiative.com/advisories/ZDI-21-821/

