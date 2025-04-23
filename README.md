# 📦 Pedidos de Compra - MVC no Protheus (ADVPL / TL++)

Projeto desenvolvido em ADVPL utilizando arquitetura MVC (Model-View-Controller) no Protheus da TOTVS.  
A rotina trata de pedidos de compra personalizados, utilizando boas práticas de organização e manutenção de código.

---

## 🧠 Visão Geral

Esta rotina customizada permite:

- Cadastro de pedidos de compra (Z01 - Cabeçalho)
- Inclusão de itens (Z02 - Itens do pedido)
- Visualização, alteração e exclusão dos dados via interface MVC
- Relacionamento entre tabelas pai/filho de forma estruturada

---

## 📂 Estrutura do Projeto

| Arquivo              | Função                                                       |
|----------------------|--------------------------------------------------------------|
| `Compras.prw`        | Ponto de entrada da rotina e carregamento dos módulos MVC    |
| `ControllerDef.tlpp` | Função `Compras()` e `MenuDef()` (navegação e browser)       |
| `ModelDef.tlpp`      | Definição do `Model` com os relacionamentos e chaves         |
| `ViewDef.tlpp`       | Definição da `View`, com fields, grids e layout da interface |

---

## ⚙️ Tecnologias Utilizadas

- ADVPL / TL++ (Protheus)
- MVC TOTVS Framework (`MPFormModel()`, `FWFormView()`, `FWBrowse()`)

---

## 🚀 Como usar

1. Compile todos os arquivos `.prw` e `.tlpp` no RPO do Protheus.
2. Registre a função `Compras()` no menu via **SIGACFG**.
3. Acesse a rotina a partir do módulo desejado (ex: SIGACOM).
4. Pronto! A interface MVC estará funcional.

---

## 🧑‍💻 Autor

**Tiago Pereira**  
Contador, desenvolvedor e entusiasta de soluções inteligentes no Protheus.  
Especialista em integrações fiscais e customizações corporativas.

---

## 📃 Licença

Este projeto é de uso livre para fins de aprendizado e aperfeiçoamento profissional.  
Sinta-se à vontade para clonar, adaptar e contribuir!

---

