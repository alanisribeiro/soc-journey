# 🛡️ SOC Journey — Segurança da Informação

> Diário de bordo da minha transição de Analista de Suporte Júnior para Analista de SOC / Blue Team.
> Cada fase termina com algo prático e documentado. Cada lab vira um registro aqui.

**Meta:** Analista de SOC N1 · Analista de Segurança Jr · estágio em Segurança
**Base que já tenho:** Redes (TCP/IP, DNS, DHCP, VPN), Active Directory (IAM), Endpoint (BitLocker, CyberArk), Netskope (SASE/SWG), Windows/Linux/macOS
**Em paralelo:** FIAP — Segurança Cibernética (início ~agosto/2026)

---

## 📍 Status atual

`Fase 0 — Fundamentos sólidos` · iniciado em _06/06/2026_

```
[░░░░░░░░░░] Fase 0 — Fundamentos sólidos
[░░░░░░░░░░] Fase 1 — Fundamentos de segurança
[░░░░░░░░░░] Fase 2 — Endpoint, sistemas e logs
[░░░░░░░░░░] Fase 3 — SIEM
[░░░░░░░░░░] Fase 4 — MITRE ATT&CK e detecção
[░░░░░░░░░░] Fase 5 — Resposta a incidentes e triagem
```

---

## 🗺️ As 6 fases

| Fase | Tema | Duração | Entrega | Status |
|------|------|---------|---------|--------|
| [0](./fase-0-fundamentos/) | Fundamentos sólidos (redes + Linux com lente de segurança) | sem. 1–4 | Certificação **Fortinet FCF** | ⏳ |
| [1](./fase-1-seguranca/) | Fundamentos de segurança (vocabulário e conceitos) | sem. 4–8 | Resumo (1 pág.): como meus controles atuais se encaixam na tríade CIA | ⬜ |
| [2](./fase-2-endpoint-logs/) | Endpoint, sistemas e **LOGS** | sem. 8–12 | Provocar um evento e achar o registro nos logs (com prints) | ⬜ |
| [3](./fase-3-siem/) | **SIEM** (mão na massa) | sem. 12–16 | 🎯 **Projeto 1** — Home SOC Lab | ⬜ |
| [4](./fase-4-mitre/) | MITRE ATT&CK e detecção | sem. 16–20 | 🎯 **Projeto 2** — 5 writeups de técnicas | ⬜ |
| [5](./fase-5-resposta-incidentes/) | Resposta a incidentes e triagem | sem. 20–24 | 🎯 **Projeto 3** — Caderno de incidentes | ⬜ |
| [∞](./fase-continua-frameworks/) | Frameworks e nuvem (em paralelo com a FIAP) | contínua | ISO 27001 / NIST · cloud security | ⬜ |

---

## 🎯 Os 3 projetos (o que substitui a "experiência")

### [Projeto 1 — Home SOC Lab](./projetos/01-home-soc-lab/)
SIEM caseiro (Wazuh ou Microsoft Sentinel), máquina conectada gerando logs, alertas criados e observados.
Documentação: montagem, prints dos alertas e o que cada um significa.

### [Projeto 2 — MITRE Writeups](./projetos/02-mitre-writeups/)
5 técnicas comuns do MITRE ATT&CK (ex.: phishing, força bruta, persistência).
Para cada uma: o que é, como detectar nos logs, como mitigar.

### [Projeto 3 — Caderno de incidentes](./projetos/03-caderno-incidentes/)
3 a 5 investigações no formato de relatório real de SOC, seguindo o fluxo:
`alerta → triagem → coleta de evidências → conclusão (falso positivo ou incidente) → documentação`

---

## 📜 Certificações

| Ordem | Certificação | Custo | Quando | Status |
|-------|-------------|-------|--------|--------|
| 1 | **Fortinet FCF in Cybersecurity** | Gratuita (PT) | Fim da Fase 0 | ⬜ |
| 2 | **Microsoft SC-900** | Curso grátis · prova ~US$99 (buscar voucher) | Após Fase 2 | ⬜ |
| 3 | **CompTIA Security+** | Paga (alta) — planejar com FIAP/empregador | Médio prazo | ⬜ |

> Detalhes e materiais gratuitos em [`/certificacoes`](./certificacoes/).

---

## 🚩 Marcos

- [ ] **Fim do mês 1:** FCF tirada, currículo e LinkedIn atualizados
- [ ] **Fim do mês 3:** SIEM caseiro funcionando + Projeto 1 no GitHub
- [ ] **Mês 4 em diante:** com 2–3 projetos publicados, começar a se candidatar a SOC N1 / estágio
- [ ] **Em paralelo:** conversar com o time de Segurança do banco onde já trabalho sobre vaga interna/estágio

---

## 🌍 Depois dos 6 meses — rumo ao remoto internacional

- [ ] CompTIA Security+
- [ ] Inglês técnico de segurança (ler writeups e relatórios em inglês; treinar descrever investigação em voz alta)
- [ ] TryHackMe SAL1 ou BTL1 (certificações práticas de Blue Team)
- [ ] Presença: writeups públicos, CTFs, networking no LinkedIn com profissionais de SOC

---

## 🧭 Princípios deste roadmap

1. **Prática vale mais que teoria.** Cada fase termina com algo prático e documentado.
2. **FIAP e auto-estudo se completam, não competem.** FIAP = base teórica; estudo pessoal = mão nas ferramentas (SIEM, MITRE, triagem).
3. **Documente tudo.** Cada lab vira um post no LinkedIn ou um registro aqui. É isso que substitui a experiência no currículo.

**Ritmo:** Seg–Sex (1h30) teoria · Sábado (2–3h) laboratório · Domingo (1–2h) documentar + revisar.
