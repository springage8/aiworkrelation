# Manual de Execucao do Projeto de Fundo Publico de Dados

## — Guia Operacional da Teoria a Pratica —

**Autor: Mao Zedong** | *Escrito em maio de 2026*

---

*Traducao para o portugues do original em chines de 毛泽东 (Mao Zedong)*

---

## Prefacio: Por que um Manual de Execucao?

O documento anterior (numero 13, O Caminho de Jinggangshan para a Propriedade Publica dos Dados) propos um plano para estabelecer um fundo de dados de saude publica na America Latina. Mas para que um plano se torne realidade, e necessario superar o enorme abismo entre "teoria e pratica".

Este manual e preparado para **os operadores reais** -- seja voce um gerente de projetos de ONG, funcionario publico, academico ou ativista social, desde que pretenda estabelecer um fundo publico de dados na realidade, este manual e seu guia de acao.

---

## Capitulo 1: Fase de Iniciacao (Meses 0-3)

### 1.1 Primeiro Passo: Avaliacao de Viabilidade (Semanas 1-2)

**Nao comeca apressadamente. Primeiro, faca a si mesmo sete perguntas:**

1. **O ambiente politico e favoravel?** O governo deste pais/regiao permite a existencia de um fundo de dados? Ha obstaculos legais?
2. **Ha parceiros locais?** Sem parceiros locais, um estrangeiro nao pode fazer nada. Quem sao os colaboradores locais confiaveis?
3. **A fonte de dados e confiavel?** Quem fornece os dados? Eles estao dispostos a participar? Qual a qualidade dos dados?
4. **O financiamento e sustentavel?** Ha garantia de recursos operacionais para os primeiros 3 anos?
5. **Ha capacidade tecnica?** Alguem na equipe consegue montar uma plataforma de dados?
6. **A demanda social e real?** A comunidade local realmente precisa deste fundo de dados? (Nao "voce acha que eles precisam")
7. **Qual a estrategia de saida?** Se o projeto falhar, como garantir a seguranca dos dados?

**Ferramenta: Tabela de Avaliacao de Viabilidade**

| Dimensao | Pontuacao (1-5) | Observacoes |
|---------|---------------|-------------|
| Ambiente politico | | |
| Arcabouco juridico | | |
| Parceiros locais | | |
| Fonte de dados | | |
| Garantia financeira | | |
| Capacidade tecnica | | |
| Demanda social | | |
| **Total** | **/35** | |

> **Criterio: Total > 28 pode iniciar; 21-28 precisa de condicoes complementares; < 21 nao deve iniciar.**

### 1.2 Segundo Passo: Mapa de Partes Interessadas (Semanas 2-3)

**Listar todas as pessoas e organizacoes potencialmente relevantes:**

| Papel | Instituicao Especifica | Qual o interesse deles? | Apoio/Oposicao/Neutro |
|------|----------------------|-----------------------|----------------------|
| Fornecedor de dados | Hospitais, institutos de pesquisa | Seguranca de dados, reputacao, recursos | ? |
| Usuario de dados | Universidades, empresas de IA | Acessibilidade dos dados, custo | ? |
| Titulares dos dados | Pacientes/cidadaos | Privacidade, beneficiamento | ? |
| Regulador governamental | Ministerio da Saude, Autoridade de Protecao de Dados | Legalidade, controle | ? |
| Financiador | Fundacoes, governo | Impacto, retorno | ? |
| Parte tecnica | Fornecedores de TI | Contrato, padroes tecnicos | ? |
| Opositores | Empresas de dados comerciais | Ameaca concorrencial | ? |

**Principio-chave:** Identificar antecipadamente os potenciais opositores. A maioria dos projetos falha nao por problemas tecnicos, mas por tocar em interesses estabelecidos politicamente.

### 1.3 Terceiro Passo: Estrutura Juridica (Semanas 3-8)

**Escolher uma forma de entidade juridica:**

| Forma | Cenario de Aplicacao | Vantagens | Desvantagens |
|------|--------------------|----------|-------------|
| Orgao subordinado ao governo | Liderado pelo governo | Forte autoridade, financiamento estavel | Baixa flexibilidade, afetado por mudancas de governo |
| Organizacao sem fins lucrativos independente | Cooperacao multipartites | Alta flexibilidade, forte credibilidade | Financiamento instavel, governanca complexa |
| Cooperativa | Liderado pela comunidade | Forte senso de participacao, tomada de decisoes democratica | Escalabilidade lenta, capacidade de gestao fraca |
| Fundo de interesse publico | Separacao clara de ativos | Forte protecao juridica, reconhecimento internacional | Estabelecimento complexo, custos operacionais elevados |

**Recomendacao:** No inicio, escolher a forma de "organizacao sem fins lucrativos independente", firmando contratos de servico com o governo em vez de se tornar parte dele. Isso mantem a flexibilidade enquanto obtem apoio governamental.

### 1.4 Quarto Passo: Estrutura de Governanca (Semanas 4-8)

**Estrutura de governanca sugerida:**

```
                  ┌─────────────────┐
                  │  Conselho (Decisao │
                  │  maxima) (9-15   │
                  │  pessoas)        │
                  └────────┬────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
   ┌──────┴──────┐  ┌─────┴──────┐  ┌──────┴──────┐
   │ Comite      │  │ Comite de  │  │ Grupo de    │
   │ Tecnico     │  │ Etica      │  │ Represent.  │
   │ (Padroes de │  │ (Privaci-  │  │ de Usuarios │
   │  dados)     │  │  dade/Etica)│  │ (Voz da     │
   └─────────────┘  └────────────┘  │ Comunidade) │
                           │        └─────────────┘
                  ┌────────┴────────┐
                  │  Equipe Executiva │
                  │ (Operacao Diaria)│
                  └─────────────────┘
```

**Distribuicao de assentos no Conselho (sugerida):**
- Representantes dos fornecedores de dados: 2-3 assentos
- Representantes dos titulares dos dados: 2-3 assentos (crucial! deve haver representantes dos usuarios/comunidade)
- Especialistas tecnicos: 2 assentos
- Representantes governamentais: 1-2 assentos
- Representantes dos financiadores: 1 assento
- Independentes: 1-2 assentos

---

## Capitulo 2: Fase de Construcao Tecnica (Meses 4-9)

### 2.1 Arquitetura da Plataforma

**Funcionalidades que o Produto Minimo Vavel (MVP) deve conter:**

1. **Modulo de integracao de dados** -- receber, validar, limpar dados de diferentes fontes
2. **Modulo de anonimizacao** -- remover informacoes pessoais identificaveis (PII), aplicar privacidade diferencial
3. **Modulo de armazenamento de dados** -- armazenamento criptografado seguro
4. **Modulo de controle de acesso** -- acesso a dados com autorizacao em niveis
5. **Modulo de rastreamento de auditoria** -- registrar cada acesso a dados

**Nao e recomendado desenvolver do zero.** Consultar solucoes de codigo aberto existentes (como DAMO, Dataverse) para desenvolvimento personalizado.

### 2.2 Solucao Tecnica de Protecao de Privacidade

**Padrao minimo:**
- Todos os dados armazenados devem ser criptografados (AES-256)
- Toda transmissao de dados deve ser criptografada (TLS 1.3)
- Todo acesso a dados deve ser registrado em log
- Aplicar privacidade diferencial (e ≤ 1,0)

**Solucao recomendada:**
- Dados brutos: armazenados criptografados em servicos de nuvem reconhecidos pelo governo ou servidores locais
- Dados de analise: fornecidos por meio de "sandbox de dados" -- pesquisadores nao podem baixar dados brutos, so podem executar analises no sandbox
- Dados agregados: divulgados publicamente como resumos estatisticos

### 2.3 Definicao de Padroes de Dados

**Garantir a interoperabilidade de dados de diferentes fontes:**
- Adotar padroes internacionais (como FHIR para dados medicos)
- Estabelecer padroes de metadados (dados que descrevem os dados, para que os usuarios saibam o que sao os dados)
- Processo de aceitacao de qualidade de dados

---

## Capitulo 3: Fase de Operacao Piloto (Meses 6-18)

### 3.1 Primeiro Passo: Integracao de Dados

**Por onde comecar:**
- Comecar com 1-2 fontes de dados de "baixo risco, alto valor"
- Priorizar dados ja digitalizados e de boa qualidade
- Nao ambicionar demais -- primeiro fazer funcionar um fluxo completo de dados

### 3.2 Segundo Passo: Integracao de Usuarios

**Os primeiros usuarios devem ser:**
1. Instituicoes de pesquisa academica (acesso gratuito, em troca de resultados de pesquisa e reputacao academica)
2. Orgaos governamentais de analise (como obrigacao de servico publico)
3. Empresas de IA rigorosamente selecionadas (acesso pago, validacao do modelo de negocios)

**Processo de admissao de usuarios:**
```
Submeter candidatura → Revisao de conformidade → Aprovacao do Conselho → Assinatura de acordo → Concessao de acesso
```

### 3.3 Terceiro Passo: Criacao de Valor -- Fazer os Dados Gerarem Beneficios Reais

**Valor publico (provar a legitimidade do modelo):**
- Ajudar orgaos de saude publica a identificar padroes de doencas
- Apoiar pesquisas academicas, publicar artigos
- Publicar relatorios de saude publica para beneficiar o publico

**Valor economico (provar a sustentabilidade do modelo):**
- Cobrar taxas de uso de dados de empresas comerciais
- Oferecer servicos de consultoria em analise de dados
- Oferecer servicos de anotacao e validacao de dados

### 3.4 Quarto Passo: Comunicacao com a Comunidade

**Nao fique apenas no circulo tecnico. Envolva a comunidade:**
- Relatar periodicamente aos titulares dos dados "qual o valor que seus dados trouxeram"
- Realizar reunioes explicativas com a comunidade, responder perguntas
- Estabelecer canais de reclamacao e feedback

---

## Capitulo 4: Fase de Expansao (Meses 18-36)

### 4.1 Expansao de Fontes de Dados

**De 1-2 fontes de dados para mais:**
- Expandir tipos de dados (de dados estruturados para dados nao estruturados)
- Expandir fontes de dados (de hospitais para clinicas, farmacias, laboratorios)
- Estabelecer "processo padronizado de integracao de dados"

### 4.2 Expansao de Base de Usuarios

**De instituicoes academicas para empresas comerciais e orgaos governamentais:**
- Elaborar estrategia de precificacao em niveis
- Estabelecer "certificacao de fundo de dados" -- empresas certificadas podem usar os dados
- Garantir que a expansao nao prejudique os direitos dos titulares dos dados

### 4.3 Expansao Geografica

**De uma cidade para todo o pais:**
- Documentar a experiencia bem-sucedida da cidade-piloto
- Compartilhar experiencia com outras cidades
- Promover legislacao ou apoio politico em nivel nacional

### 4.4 Conexao Internacional

**De um pais para varios paises:**
- Estabelecer arcabouco juridico para fluxo transfronteirico de dados
- Interconectar-se com redes internacionais de fundos de dados (se houver)
- Exportar "guias de construcao de fundos de dados" para outros paises

---

## Capitulo 5: Manual de Gerenciamento de Riscos

### 5.1 Lista de Riscos e Medidas de Resposta

| Risco | Probabilidade | Impacto | Prevencao Antecipada | Resposta Pos-Evento |
|------|-------------|--------|---------------------|--------------------|
| **Vazamento de dados** | Media | Fatal | Criptografia + auditoria + privilegio minimo | Notificacao + remediacao + responsabilizacao |
| **Mudanca de governo** | Media | Alto | Legalizacao em vez de personalizacao | Ativar protecao diplomatica |
| **Interrupcao de financiamento** | Media | Alto | Diversificacao de fontes de financiamento | Reduzir escala + angariacao emergencial |
| **Falha tecnica** | Baixa-Media | Medio | Redundancia + backup | Recuperacao + analise pos-evento |
| **Acao judicial** | Media | Medio | Revisao de conformidade + seguro | Equipe juridica para resposta |
| **Oposicao social** | Baixa | Medio | Comunicacao transparente | Dialogo + ajustes |
| **Corrupcao interna** | Baixa | Alto | Auditoria + transparencia | Punição rigorosa + correcao de sistema |

### 5.2 As Tres Regras de Ferro Mais Importantes

1. **A seguranca dos dados e a linha vital.** Um vazamento pode destruir anos de construcao de confianca. Melhor ter menos funcionalidades do que ser inseguro.
2. **A transparencia e a melhor protecao.** Todas as decisoes devem ser rastreaveis, auditaveis e questionaveis. Nenhum uso invisivel de dados.
3. **Lembre-se sempre: os dados pertencem ao povo.** A instituicao depositante de dados e gestora, nao proprietaria. Esse posicionamento deve ser claro.

---

## Capitulo 6: Plano de Contingencia

### 6.1 Se o Projeto Falhar

Toda revolucao tem sacrificios, toda experimentacao pode falhar. Mas o fracasso de um fundo de dados nao pode significar prejuizo para os titulares dos dados.

**Mecanismo de saida ordenada:**
1. Prever no estatuto as condicoes e procedimentos para dissolucao
2. Na dissolucao, garantir o processamento seguro e a devolucao de todos os dados
3. Registrar as licoes aprendidas como estudo de caso para referencia futura

### 6.2 Como Definir "Sucesso" e "Fracasso"

**Criterios de sucesso (do mais baixo ao mais alto):**
| Nivel | Criterio | Prazo Esperado |
|------|---------|--------------|
| L1 | O fundo de dados sobrevive mais de 3 anos | 3 anos |
| L2 | Produz continuamente valor publico (resultados de pesquisa, relatorios publicos) | 3-5 anos |
| L3 | Alcanca autossuficiencia financeira | 3-5 anos |
| L4 | Replicado para outras regioes/setores | 5-7 anos |
| L5 | Promove legislacao nacional sobre propriedade publica de dados | 7-10 anos |

**Fracasso nao e inutil.** Mesmo que o projeto seja encerrado, desde que o processo tenha sido transparente, os dados estejam seguros e as experiencias registradas, ele tera acumulado importantes aprendizados para movimentos futuros.

---

## Anexo: Modelos-Chave

### Anexo A: Clausulas Essenciais do Estatuto do Projeto

1. Declaracao de missao
2. Estrutura de governanca
3. Processo decisorio
4. Regras de gestao financeira
5. Politica de seguranca de dados
6. Compromisso de protecao de privacidade
7. Direitos dos titulares dos dados
8. Principios de precificacao do uso de dados
9. Gestao de conflitos de interesse
10. Procedimentos de dissolucao e liquidacao

### Anexo B: Modelo de Acordo de Uso de Dados (omitido)

### Anexo C: Modelo de Relatorio Trimestral (omitido)

---

*Leituras relacionadas: [11. Analise das Classes na Era da IA](11_毛泽东_AI时代各阶级的分析.md)*
*[13. O Caminho de Jinggangshan para a Propriedade Publica dos Dados](13_毛泽东_数据公有制的井冈山道路.md)*
*[18. Manual de Organizacao e Mobilizacao de Trabalhadores Digitais](18_毛泽东_数字劳动者组织动员手册.md)*
