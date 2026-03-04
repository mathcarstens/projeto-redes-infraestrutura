#  Projeto de Redes – Infraestrutura com Aplicação Web

##  Visão Geral

Este projeto consiste na implementação de uma infraestrutura de rede funcional, conectada à Internet, utilizando serviços reais em ambiente Linux.

O objetivo foi configurar os principais serviços necessários para o funcionamento de uma rede local segura, segmentada e monitorada, além da implantação de uma aplicação web para usuários finais.

---

##  Arquitetura da Rede

- Dispositivo de borda com interface **LAN** e **WAN**
- Separação em sub-redes internas
- Roteamento entre sub-redes
- Acesso à Internet via **NAT**
- Políticas de segurança aplicadas via firewall

---

##  Serviços Implementados

- **DHCP** – distribuição automática de endereços IP  
- **DNS** – resolução de nomes internos  
- **Firewall (iptables)** – controle e filtragem de tráfego  
- **NAT** – acesso das redes internas à Internet  
- **NTP** – sincronização de horário  
- **Wi-Fi (hostapd)** – ponto de acesso  
- **Servidor Web (Apache2)** – aplicação web funcional  
- **Monitoramento (Netdata)** – análise de desempenho e serviços  
- **Diagnóstico (Nmap)** – testes e varredura de rede  

---

##  Monitoramento

O sistema de monitoramento permite visualizar:

- Uso de CPU e memória  
- Tráfego de rede  
- Status dos serviços  
- Funcionamento da aplicação web  

O painel pode ser acessado via navegador dentro da rede.

---

## Segurança

- Política padrão restritiva no firewall  
- Regras específicas de liberação e bloqueio  
- Controle seletivo de acesso a serviços externos  
- Separação lógica entre sub-redes  

---

##  Ambiente de Implementação

- Sistema operacional: **Linux**
- Serviços configurados manualmente
- Implementação em ambiente real ou virtualizado
- Utilização de ferramentas reais de rede

---

##  Documentação

O repositório contém o relatório completo em PDF com:

- Descrição da topologia  
- Justificativa das ferramentas escolhidas  
- Passo a passo das configurações  
- Testes e resultados obtidos  

---

##  Objetivo Acadêmico

Projeto desenvolvido para aplicação prática dos conceitos de:

- Redes de Computadores  
- Infraestrutura de serviços  
- Segurança de rede  
- Monitoramento e administração de sistemas  
