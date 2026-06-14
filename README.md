# 💸 App de Organização de Finanças Pessoais com Vibe Coding:

# PRD Refinado, com as orientações do Copilot: 

## 📝 Prompt Final 
[bloco de código com PRD]

```
   #PRD – App de Organização de Finanças Pessoais

Contexto: Criar um aplicativo de organização financeira pessoal que funcione por meio de conversas naturais com o usuário, em tom explicativo e acessível.O objetivo é simplificar o controle financeiro sem depender de formulários manuais ou planilhas complexas.

Problema

Muitas pessoas não conseguem manter um controle financeiro porque:

- Os aplicativos exigem muita entrada manual de dados.

- A criação de orçamentos é vista como tediosa e difícil de compreender.

Necessidade: Uma solução que permita controlar as finanças por meio de conversas simples, com agentes de IA capazes de criar planos e recomendações personalizadas de economia e planejamento.

Público-Alvo

- Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicação.

- Principalmente iniciantes que não têm familiaridade com planilhas ou apps tradicionais.

Funcionalidades-Chave

1. Registrar gastos via chat em linguagem natural.

2. Classificação automática das transações.

3. Definição e acompanhamento de metas financeiras.

4. Agente Financeiro: dicas de economia personalizadas.

5. Relatórios simples e personalizados.

6. Cronograma de planejamento financeiro: visão clara de médio e longo prazo.

7. Sugestões para ampliar receita: oportunidades de renda extra.

Design Universal

O aplicativo deve seguir os princípios de Design Universal, garantindo que seja acessível e agradável para o máximo de usuários possíveis, independentemente de idade, experiência digital ou limitações físicas.

- Interface clara e intuitiva.

- Linguagem simples e explicativa.

- Compatibilidade com leitores de tela e recursos de acessibilidade.

- Experiência consistente em diferentes dispositivos.

Entregável da IA

- Gerar um plano de MVP com:

  - Principais telas (chat, relatórios, metas).

  - Recursos necessários (IA de NLP, categorização automática, gráficos simples).

  - Esboço de validação inicial (testar com usuários iniciantes).

- Usar tom educativo e linguagem clara em português do Brasil.

```

## 📱Lista de funcionalidades do Aplicativo

## Registro de Gastos
- Inserção de despesas e receitas por meio de conversas em linguagem natural.
- Eliminação da necessidade de formulários manuais ou planilhas complexas.

## Classificação Automática
- Organização automática das transações em categorias.
- Facilita a visualização dos principais tipos de gastos.

## Metas Financeiras
- Definição de objetivos financeiros personalizados.
- Acompanhamento do progresso em tempo real.

## Agente Financeiro
- Recomendações de economia adaptadas ao perfil do usuário.
- Dicas práticas para melhorar o controle financeiro.

## Relatórios Personalizados
- Visualização de relatórios simples e claros.
- Gráficos e resumos acessíveis para iniciantes.

## Planejamento Financeiro
- Cronograma de médio e longo prazo para dar clareza às decisões.
- Orientação sobre como estruturar planos financeiros futuros.

## Ampliação de Receita
- Sugestões de oportunidades para aumentar a renda.
- Possibilidades de diversificação financeira.

## Design Universal
- Interface clara e intuitiva.
- Linguagem simples e explicativa.
- Compatibilidade com recursos de acessibilidade (ex.: leitores de tela).
- Experiência consistente em diferentes dispositivos.

---

## 🤖Interações com o Lovable: 
> 1️⃣
> Crie um app de finanças com base no seguinte PRD (Product Requirements Document): (#PRD)

> 2️⃣
> Não está claro no app as funcionalidades e está travando para uso e conversas, só vejo icone metas e relatorios. Não estou conseguindo digitar e acessar as possibilidades. Pode verificar as funcionalidades por completo. Fazer todos os testes necessários para que o app fique pronto pra uso?

> 3️⃣
> Orientações Técnicas para Build.
O projeto deve ser configurado para evitar externalização indevida de módulos durante o processo de build com Vite.
Garantir que o arquivo app.chat.$threadId.tsx seja corretamente incluído no bundle.
Caso seja necessário externalizar módulos, adicionar explicitamente em build.rollupOptions.external dentro do vite.config.js.
Revisar imports dinâmicos e caminhos de arquivos para evitar falhas de resolução.
Validar o build com vite build em modo verbose para confirmar que não há módulos não intencionais sendo externalizados.

---

# 📷Comprovação das Interações e Testes aplicados:
<img width="1887" height="945" alt="Captura de tela 2026-06-14 172337" src="https://github.com/user-attachments/assets/e326302b-fca2-4078-9e91-becf3e78f4ec" />

---

## 📷Resultado final: 
Aqui estão alguns registros das telas do app:


**Tela de login:**
<img width="1097" height="847" alt="Captura de tela 2026-06-14 181049" src="https://github.com/user-attachments/assets/667c5a48-a04f-488f-adac-98d6b11eb71e" />
---


**Tela inicial:**
<img width="1112" height="808" alt="Captura de tela 2026-06-14 193546" src="https://github.com/user-attachments/assets/d10e4749-9356-4599-a450-f94150d21bec" />
---


**Aba de metas:**
<img width="1121" height="857" alt="Captura de tela 2026-06-14 175352" src="https://github.com/user-attachments/assets/06f8c633-4950-4a1d-9ad7-ff488d4618f5" />
---


**Aba de Relatórios:**
<img width="1092" height="683" alt="Captura de tela 2026-06-14 175413" src="https://github.com/user-attachments/assets/22c3732d-28a0-46e0-9fe3-8afd59e02844" />

---


## 💡Reflexões:

 - O que funcionou bem?
As interações com o Copilot trouxeram bons resultados e demonstrou repertorio e clareza nas informacoes.
 
  - O que não funcionou como o esperado?
O Lovable apresentou algumas falhas no uso e principalmente no momento de publicar. O lovable é bem limitado o uso free.

- O que aprendeu sobre conversar com IAs?
Requer testes, clareza, objetivida e repertório.
Saber apresentar bem o que quer e como quer e quanto mais se pensar e direcionar as amplas possibilidades melhores resultados poderá ter. E vamos dar destaque aos uso de mais de uma IA em conjunto que traz agilidade e praticidade aos resultados. O lovable é bom pra ser um chechlist de requisitos e o que é necessário para um app e um site utilizavel, bom para testar ideias.

## Conclusão:

O uso da IA e de toda nova ferramenta se desenvolve com a prática, então tem que testar possibilidades e linguagem e ler os resultados apresentados. Não adianta querer ser imediatista e criar altas expectativas com uma ferramenta na qual você ainda não a conhece por completo.
  

