# 🔧 Auto Center Veloz

Site institucional com canal de comunicação para a **Auto Center Veloz**, oficina mecânica especializada em manutenção preventiva e corretiva de veículos de passeio.

> Projeto da disciplina **Design Profissional — Produção de Portfólio & Desenvolvimento Empresarial**
> Estudo de Caso 3: Oficina e Auto Center Veloz

---

## 📋 1. Briefing do problema

A Auto Center Veloz é liderada por Eduardo (gerente de oficina) e Henrique (financeiro e compras). Tem excelente reputação técnica, **5 elevadores automotivos**, **6 mecânicos** e **2 recepcionistas**.

Hoje, o cadastro do veículo e o orçamento são feitos em papel na recepção, e as autorizações de troca de peças são pedidas por telefone.

### Dor do cliente

Com o crescimento da base de clientes, o telefone da recepção não para de tocar com pessoas querendo saber:

- o status do conserto;
- se o carro já está pronto;
- fotos das peças com defeito.

### Consequências

- Mecânicos interrompem o trabalho para responder à recepção.
- Clientes demoram horas para aprovar orçamentos.
- O pátio fica lotado de carros parados aguardando resposta.
- Risco de avaliações negativas na internet por falha de comunicação.

### Oportunidade

A concorrência é formada por concessionárias (caras, mas com relatórios digitais) e oficinas pequenas e informais. A Auto Center Veloz pode unir a **confiança técnica** que já tem a um **canal rápido e transparente** de comunicação e aprovação de serviços.

---

## 💡 2. Solução escolhida: Site institucional

### Por que um site?

| Motivo | Explicação |
| --- | --- |
| **Sem instalação** | O cliente acessa por qualquer celular ou computador, sem baixar aplicativo. |
| **Resolve a dor principal** | Permite relatar o problema e acompanhar o serviço sem ligar para a oficina. |
| **Custo baixo** | Hospedagem gratuita (GitHub Pages) e manutenção simples. |
| **Presença na internet** | Funciona também como vitrine de serviços, ajudando contra concorrentes informais. |
| **Evolução futura** | Pode crescer para um sistema com cadastro e banco de dados. |

### Como o site reduz as ligações

1. **Relato do problema:** o cliente descreve o defeito com suas próprias palavras, informando dados do veículo, quando o problema acontece e há quanto tempo.
2. **Acompanhamento do serviço:** painel com etapas e barra de progresso, para o cliente ver o status sem telefonar.
3. **Comunicação clara:** seção "O que acontece depois?" explica o fluxo e diminui a ansiedade do cliente.

---

## 🖼️ 3. Protótipo / Telas

O site é uma página única (*one page*) com as seguintes seções:

| Seção | Descrição |
| --- | --- |
| **Cabeçalho** | Logo e menu de navegação: Início, Relatar Problema, Serviços, Acompanhar Serviço, Contato. |
| **Tela principal** | Chamada "Está com algum problema no seu veículo?" e botão "Relatar um problema". |
| **Relate seu problema** | Formulário com dados do cliente, dados do veículo, tipo de problema, quando acontece, descrição livre, tempo e mudanças recentes. |
| **O que acontece depois?** | Quatro etapas: relato recebido, análise, contato e diagnóstico. |
| **Acompanhe seu veículo** | Exemplo com Honda Civic 2020, placa ABC-1234, e barra de progresso. |
| **Serviços** | Cards: revisão preventiva, troca de óleo, freios, suspensão, diagnóstico e troca de peças. |
| **Por que escolher** | Diferenciais da oficina: 5 elevadores, 6 mecânicos, transparência e comunicação. |
| **Contato** | Telefone, WhatsApp, endereço e horário de atendimento. |

> 📸 **Capturas de tela:** adicione imagens do site na pasta `docs/` e referencie aqui, por exemplo:
> `![Tela principal](docs/tela-principal.png)`

### Identidade visual

- **Cores:** preto, cinza escuro, vermelho e branco.
- **Estilo:** moderno, com cards escuros, bordas arredondadas e sombras leves.
- **Responsivo:** adaptado para computador, tablet e celular com *media queries*.

---

## 🏗️ 4. Arquitetura utilizada

O projeto é **estático**: apenas HTML e CSS, sem JavaScript, frameworks, back-end ou banco de dados.

```
autocenter-veloz/
├── index.html    # Estrutura e conteúdo da página
├── style.css     # Estilos e responsividade
├── README.md     # Documentação do projeto
├── LICENSE       # Licença MIT
└── .gitignore    # Arquivos ignorados pelo Git
```

### Tecnologias

- **HTML5**: estrutura semântica (`header`, `main`, `section`, `footer`).
- **CSS3**: variáveis CSS, Flexbox, Grid e Media Queries.

### Limitações da versão atual

Os formulários e botões (**ENVIAR RELATO**, aprovar/recusar) são **apenas demonstração visual**. Como não há JavaScript nem servidor, nenhum dado é enviado ou armazenado.

### Próximos passos (evolução)

- Back-end para receber os relatos e notificar a recepção.
- Login do cliente e consulta real do status do veículo.
- Envio de orçamento com fotos das peças e aprovação online.

---

## ▶️ 5. Como executar

### Localmente

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/autocenter-veloz.git
   ```
2. Entre na pasta do projeto:
   ```bash
   cd autocenter-veloz
   ```
3. Abra o arquivo `index.html` com duplo clique ou arraste-o para o navegador.

Não é necessário instalar nada.

### Publicação no GitHub Pages

1. No repositório, acesse **Settings → Pages**.
2. Em **Source**, escolha a branch `main` e a pasta `/ (root)`.
3. Salve. O site ficará disponível em `https://SEU-USUARIO.github.io/autocenter-veloz/`.

---

## 🔒 6. Segurança

Este projeto **não contém** senhas, tokens, chaves de API ou qualquer credencial, nem no código nem no histórico de commits.

Os dados de contato do site (telefone, WhatsApp e endereço) são **fictícios**, usados apenas para demonstração.

---

## 📄 7. Licença

Distribuído sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👤 Autor

**Seu Nome**
Disciplina de Design Profissional — Prof. Sedenilso Antonio Machado
GitHub: [@SEU-USUARIO](https://github.com/SEU-USUARIO)
