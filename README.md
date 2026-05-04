# Desafio-de-projeto-DIO-LLM

# 📚 Miniguia de Estudos: Infraestrutura de Redes e Segurança

Este repositório contém a documentação de um Caderno Temático desenvolvido no **NotebookLM**, como parte do desafio prático da DIO. O projeto explora o uso de Inteligência Artificial para potencializar o aprendizado ativo em arquitetura de redes e segurança cibernética.

---

## 🎯 Contexto e Objetivos

O tema escolhido para este caderno foi **"Estratégias de Alta Disponibilidade e Segurança em Redes Corporativas"**. 

**Objetivos de estudo:**
* Compreender a implementação de redundância e agregação de links (LACP) para otimização de performance.
* Analisar a aplicação de protocolos de roteamento dinâmico (como BGP) em ambientes de missão crítica.
* Explorar a segmentação de redes (VLANs) e túneis seguros (VPN IPsec) para mitigação de vulnerabilidades.

---

## 📑 Curadoria de Fontes

Para alimentar o NotebookLM, foram selecionadas fontes técnicas que garantem uma base teórica e prática sólida:

1. **RFC 4271 (A Border Gateway Protocol 4):** Documentação oficial para entendimento profundo de roteamento dinâmico.
2. **IEEE 802.1AX-2008:** Padrão técnico para Agregação de Link (LACP).
3. **Guia de Melhores Práticas em Firewall de Próxima Geração (NGFW):** Focado em políticas de segurança perimetral.
4. **Manual de Redes de Alta Disponibilidade:** Focado em arquiteturas que minimizam pontos únicos de falha.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

Abaixo, registro as estratégias de interação com o NotebookLM e os aprendizados obtidos no processo:

### 1. Prompts de Exploração
*   **Pergunta:** "Explique como a implementação de BGP (AS 65400) melhora a resiliência em uma conexão Site-to-Site."
*   **Resultado:** A IA forneceu uma explicação técnica sobre convergência de rotas, mas inicialmente ignorou a questão da latência.
*   **Refinamento:** "Considere agora o impacto na performance de links ópticos de longa distância."

### 2. Dificuldades e Troubleshooting
*   **O Desafio:** Inicialmente, as respostas sobre segmentação de redes eram genéricas.
*   **A Solução:** Foi necessário fornecer contextos específicos sobre infraestrutura FTTH e mitigação de broadcast para que o NotebookLM gerasse insights aplicáveis a cenários reais de expansão de rede.

---

## 📖 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
A modernização de infraestruturas exige uma abordagem em camadas. A utilização de **VPNs IPsec** aliada ao roteamento dinâmico permite que unidades remotas se comuniquem com redundância automática. A segurança é reforçada não apenas no perímetro, mas na segmentação interna via VLANs, garantindo que o tráfego seja isolado e monitorado via ferramentas como Zabbix e Grafana.

### 📝 Glossário
*   **LACP (Link Aggregation Control Protocol):** Protocolo que agrupa vários links físicos em um único link lógico.
*   **BGP (Border Gateway Protocol):** Protocolo de roteamento que gerencia como os pacotes são passados através da internet.
*   **VLAN (Virtual Local Area Network):** Segmentação lógica de uma rede física para melhorar a segurança e o desempenho.
*   **VPN Site-to-Site:** Conexão segura que une duas redes distintas através de um túnel criptografado pela internet.

### 🔄 Prompts Reutilizáveis para Revisão
*   "Resuma as principais métricas de monitoramento para um ambiente de firewalls em alta disponibilidade."
*   "Quais são os passos fundamentais para configurar um failover de rota entre dois provedores utilizando BGP?"
*   "Gere um checklist de segurança para auditoria em infraestrutura de rede local."

---
