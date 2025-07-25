
# ✅ OpenTelemetry: Checklist + Roadmap para Especialistas

Este repositório contém um roadmap completo para quem deseja se tornar **especialista em OpenTelemetry**, com etapas práticas, semanais e objetivos claros.

---

## 🟩 FASE 1 – Fundamentos de Observabilidade (Semana 1)
- [ ] Entender o que é observabilidade e a diferença para monitoramento
- [ ] Estudar os 3 pilares: **logs**, **métricas** e **traces**
- [ ] Ler o livro “Observability Engineering” (ou resumos)
- [ ] Fazer curso introdutório sobre SRE / Observabilidade (Coursera / YouTube)

---

## 🟨 FASE 2 – Introdução ao OpenTelemetry (Semana 2)
- [ ] Entender a arquitetura do OpenTelemetry (SDK, Collector, Exporters)
- [ ] Estudar o site oficial: https://opentelemetry.io/docs
- [ ] Aprender o que é instrumentação automática x manual
- [ ] Estudar o que é contexto de trace e propagação (Trace Context, Baggage)

---

## 🟧 FASE 3 – Ambiente Local com OpenTelemetry (Semana 3)
- [ ] Montar ambiente com Docker: App simples + OTel Collector + Jaeger + Prometheus
- [ ] Gerar métricas e traces localmente
- [ ] Visualizar traces no Jaeger
- [ ] Enviar métricas para Prometheus e visualizar no Grafana

---

## 🟨 FASE 4 – Instrumentação por Linguagem (Semanas 4 e 5)
- [ ] Instrumentação manual em app simples (HTTP/DB) – *Node.js*
- [ ] Instrumentação automática – *Python*
- [ ] Exportar dados via OTLP para Collector – *Java*
- [ ] Adicionar atributos (labels) em métricas e traces

---

## 🟥 FASE 5 – Exporters e Ecossistema (Semana 6)
- [ ] Exportar dados para Grafana Tempo / Loki
- [ ] Exportar dados para Datadog, NewRelic, AWS X-Ray
- [ ] Utilizar formatos: OTLP, Prometheus Remote Write, Zipkin/Jaeger Exporters

---

## 🟦 FASE 6 – Collector Avançado (Semana 7)
- [ ] Criar pipelines com Processors (batch, attributes, sampling)
- [ ] Criar Receiver customizado
- [ ] Aplicar filtros para dados sensíveis
- [ ] Criar exporters customizados (avançado)

---

## 🟫 FASE 7 – Nuvem e Kubernetes (Semana 8)
- [ ] Deploy do Collector no Kubernetes via Helm
- [ ] Configurar autoscaling do Collector
- [ ] Instrumentar microserviços
- [ ] Monitorar o OTel Collector com Prometheus

---

## 🟪 FASE 8 – Especialização e Contribuições
- [ ] Contribuir para repositórios OpenTelemetry no GitHub
- [ ] Participar da comunidade CNCF / Slack oficial
- [ ] Escrever artigo técnico ou dar palestra sobre OTel
- [ ] Criar laboratório com simulação de falhas rastreáveis

---

## 📚 Recursos Complementares

| Tipo     | Nome                                 | Link                                                                 |
|----------|--------------------------------------|----------------------------------------------------------------------|
| Livro    | Observability Engineering            | https://www.oreilly.com/library/view/observability-engineering/9781492076439/ |
| Curso    | OpenTelemetry 101 (CNCF / edX)       | https://www.edx.org/course/introduction-to-opentelemetry            |
| Docs     | OpenTelemetry Docs                   | https://opentelemetry.io/docs                                       |
| Slack    | CNCF Slack (canal `#opentelemetry`)  | https://slack.cncf.io/                                              |

---

## 🧪 Quer começar com um projeto de exemplo?

Peça um `docker-compose` com:
- OpenTelemetry Collector
- App Instrumentado (Python ou Node.js)
- Jaeger
- Prometheus
- Grafana

E já comece a praticar de verdade!