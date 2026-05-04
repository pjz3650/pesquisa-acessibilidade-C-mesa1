# Pesquisa Acessibilidade Digital — Dimensão C: Legislação

> Projeto DAD 2026 · Aulas 17–19 · Instituto J&F — Escola de Tecnologia

## Sobre esta pesquisa

Esta pesquisa investiga a **Dimensão C** do projeto: a legislação que obriga acessibilidade digital no Brasil e no mundo, e as consequências práticas para desenvolvedores e empresas. A pergunta central é: **quais leis obrigam acessibilidade digital e quais são as consequências de descumpri-las?**

## O que descobrimos (Principais Achados)

- **A LBI obriga acessibilidade digital no Brasil desde 2015, mas o artigo central nunca foi regulamentado.** O Art. 63 da Lei 13.146/2015 determina que todo site de empresa com sede no Brasil deve ser acessível — mas, após 10 anos de vigência, o Ministério Público Federal recomendou em agosto de 2025 que o governo regulamente o dispositivo em até 45 dias, porque sem regulamentação não há parâmetros técnicos obrigatórios nem sanções definidas. Fonte: [MPF/SP, 2025](https://www.mpf.mp.br/sp/sala-de-imprensa/noticias-sp/mpf-recomenda-regulamentacao-de-trecho-da-lei-brasileira-de-inclusao-sobre-acessibilidade-na-internet).

- **Falta de acessibilidade pode ser enquadrada como crime no Brasil.** O Art. 88 da LBI prevê reclusão de 1 a 3 anos e multa para quem praticar, induzir ou incitar discriminação em razão de deficiência — e a falta de acessibilidade é entendida como forma de discriminação. Fonte: [Lei 13.146/2015 — Planalto](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13146.htm).

- **Nos EUA, a jurisprudência já consolidou que sites estão sob a ADA.** O caso Robles v. Domino's Pizza (2019) virou marco: a Suprema Corte negou revisão do recurso da Domino's, mantendo a decisão de que a ADA se aplica a sites e apps de empresas com lojas físicas. Em 2023, foram registrados mais de 4.600 processos federais de acessibilidade web nos EUA, concentrados em Nova York, Califórnia e Flórida. Fontes: [Justia, 9th Circuit](https://law.justia.com/cases/federal/appellate-courts/ca9/17-55504/17-55504-2019-01-15.html), [UsableNet 2023 Report via 3PlayMedia](https://www.3playmedia.com/blog/key-takeaways-usablenets-ada-web-app-report/).

- **O Brasil tem o e-MAG desde 2005, mas só vale para o governo.** O Modelo de Acessibilidade em Governo Eletrônico foi institucionalizado pela Portaria nº 3/2007 e tornado obrigatório nos sítios do governo federal — mas nunca foi estendido ao setor privado. Para empresas como PicPay e Banco Original, o e-MAG é referência, não obrigação. Fonte: [Governo Digital — eMAG](https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/modelo-de-acessibilidade).

- **O padrão global de fato é o WCAG 2.1 nível AA.** Publicado pelo W3C em 2018, o WCAG 2.1 cobre 17 novos critérios em relação ao 2.0, principalmente sobre acessibilidade mobile. É o padrão referenciado pela maioria das leis e decisões judiciais no mundo, incluindo a sentença final do caso Domino's (2021), que obrigou a empresa a se adequar à WCAG 2.0. Fonte: [WCAG 2.1 — W3C Brasil](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/).

## Legislação — Linha do tempo

A tabela abaixo é a base do infográfico (`evidencias/infografico-linha-tempo.png`).

| Ano | Marco | Tipo | Implicação |
|-----|-------|------|------------|
| 1990 | ADA sancionada nos EUA | Lei | Lei de direitos civis para PCD; ainda não menciona internet. |
| 1999 | W3C publica WCAG 1.0 | Padrão técnico | Primeira tentativa de padronização global de acessibilidade web. |
| 2005 | 1ª versão do e-MAG | Padrão técnico (BR) | Brasil cria seu próprio modelo, baseado no WCAG. |
| 2007 | Portaria nº 3 institucionaliza o e-MAG | Norma infralegal | Torna o e-MAG obrigatório no governo federal brasileiro. |
| 2008 | WCAG 2.0 — princípios POUR | Padrão técnico | Define os 4 princípios (Perceptível, Operável, Compreensível, Robusto). |
| 2015 | Sanção da LBI — Lei 13.146 | Lei | Art. 63 obriga acessibilidade em todos os sites de empresas com sede no Brasil. Art. 88 criminaliza discriminação. |
| 2018 | WCAG 2.1 | Padrão técnico | Inclui critérios para mobile. Adotado pela União Europeia como padrão oficial. |
| 2019 | Caso Robles v. Domino's | Jurisprudência (EUA) | Suprema Corte mantém decisão: ADA se aplica a sites e apps. |
| 2021 | Sentença final Domino's | Jurisprudência (EUA) | Domino's obrigada a adequar site ao WCAG 2.0. |
| 2023 | 4.605 processos ADA por acessibilidade web | Estatística | Aumento de ~42% sobre 2022 nos EUA. |
| 2023 | WCAG 2.2 publicado | Padrão técnico | Adiciona 9 novos critérios. |
| Mar/2025 | ABNT NBR 17.225 publicada | Norma técnica (BR) | Primeira norma técnica brasileira específica para acessibilidade web. |
| Ago/2025 | MPF dá 45 dias para regulamentar Art. 63 | Ação regulatória | Após 10 anos, lei ainda sem parâmetros técnicos obrigatórios nem sanções. |

### O paradoxo brasileiro

O Brasil tem **lei** (LBI), tem **norma técnica** (ABNT NBR 17.225) e tem **modelo de referência** (e-MAG). Mas, sem a regulamentação do Art. 63 da LBI, a norma técnica é apenas recomendação. Na prática, isso significa:

- Empresas privadas têm **obrigação legal** (Art. 63), mas **não há parâmetros oficiais** definindo o que cumprir.
- A fiscalização é difícil porque não há sanções específicas.
- Quem é processado responde pela via genérica (danos morais, ação civil pública), não por descumprimento direto de norma técnica.

Compare com os EUA: também não tem regulamentação técnica federal específica, mas a jurisprudência (Robles v. Domino's) consolidou que ADA + WCAG 2.0 AA é o padrão de fato — e isso gerou uma indústria de litígio com mais de 4.600 processos por ano.

## Como isso afeta o nosso trabalho como desenvolvedores

Três práticas concretas que um dev júnior do Grupo J&F (PicPay, Banco Original) pode adotar a partir de amanhã:

### 1. Documentar conformidade WCAG no código

Comentar decisões de acessibilidade citando o critério WCAG correspondente. Em uma eventual ação judicial, o histórico do Git vira evidência de boa-fé.

```javascript
// a11y: aria-expanded sincronizado com o estado do menu
// WCAG 2.1 — Critério 4.1.2 (Name, Role, Value) — Nível A
menuButton.setAttribute('aria-expanded', isOpen);
menuButton.setAttribute('aria-controls', 'main-menu');

// a11y: foco gerenciado ao abrir modal
// WCAG 2.1 — Critério 2.4.3 (Focus Order) — Nível A
if (isOpen) modalCloseButton.focus();
```

### 2. Rodar Lighthouse/axe-core no CI/CD

Adicionar checagem automática no pipeline que falha o build se o score de acessibilidade cair abaixo de um threshold. Exemplo com axe-core e Playwright:

```javascript
import { test, expect } from '@playwright/test';
import AxeBuilder from '@axe-core/playwright';

test('homepage não deve ter violações WCAG 2.1 AA', async ({ page }) => {
  await page.goto('/');
  const results = await new AxeBuilder({ page })
    .withTags(['wcag2a', 'wcag2aa', 'wcag21a', 'wcag21aa'])
    .analyze();
  expect(results.violations).toEqual([]);
});
```

Isso gera **evidência auditável** de que a equipe testa acessibilidade em toda release — exatamente o tipo de processo que evidencia conformidade com a LBI.

### 3. Referenciar WCAG nos tickets de design

Quando o designer enviar um mockup com contraste baixo ou interação dependente apenas de mouse, responder no ticket citando o critério específico:

```
Bloqueando o ticket #1234.
O contraste do texto secundário (#999 sobre #FFF) é 2.85:1.
WCAG 2.1 — 1.4.3 (Contrast Minimum) Nível AA exige no mínimo 4.5:1
para texto normal. Sugestão: usar #595959 (contraste 7:1).
```

Isso sobe a discussão do plano individual para o organizacional, gera registro escrito e protege o desenvolvedor quando alguém perguntar "por que atrasou?".

## Referências

1. **BRASIL.** Lei nº 13.146, de 6 de julho de 2015 (Lei Brasileira de Inclusão da Pessoa com Deficiência). Brasília, 2015. Disponível em: https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13146.htm
2. **MINISTÉRIO PÚBLICO FEDERAL — SP.** MPF recomenda regulamentação de trecho da Lei Brasileira de Inclusão sobre acessibilidade na internet. 2025. Disponível em: https://www.mpf.mp.br/sp/sala-de-imprensa/noticias-sp/mpf-recomenda-regulamentacao-de-trecho-da-lei-brasileira-de-inclusao-sobre-acessibilidade-na-internet
3. **GOVERNO DIGITAL — Ministério da Gestão e da Inovação em Serviços Públicos.** Modelo de Acessibilidade em Governo Eletrônico (e-MAG). Disponível em: https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/modelo-de-acessibilidade
4. **W3C.** Web Content Accessibility Guidelines (WCAG) 2.1 — Tradução PT-BR. 2018. Disponível em: https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/
5. **JUSTIA.** Robles v. Domino's Pizza, LLC, No. 17-55504 (9th Cir. 2019). Disponível em: https://law.justia.com/cases/federal/appellate-courts/ca9/17-55504/17-55504-2019-01-15.html
6. **3PLAY MEDIA.** Key Takeaways from UsableNet's 2023 Year-End Digital Accessibility Lawsuit Report. 2024. Disponível em: https://www.3playmedia.com/blog/key-takeaways-usablenets-ada-web-app-report/
7. **CGI.BR / CEWEB.BR.** Desenvolvida com coordenação do Ceweb.br, nova norma da ABNT estabelece requisitos para melhorar a acessibilidade de sites. 2025. Disponível em: https://www.cgi.br/noticia/releases/desenvolvida-com-coordenacao-do-ceweb-br-nova-norma-da-abnt-estabelece-requisitos-para-melhorar-a-acessibilidade-de-sites/

---

> **Mesa:** [Davi Franco, Giovanna Medeiros, Davi Dias, Arthur do Vale, Kevin Jun]

> **Dimensão sorteada:** C — Legislação Brasileira e Internacional

> **Entrega:** Aula 19 · DAD 2026
