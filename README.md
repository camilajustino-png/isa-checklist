# 🏥 ISA Saúde — Checklist Home Care 2026

> **Instrumento de Avaliação para Apoio e Assistência ao Paciente em Domicílio**  
> Desenvolvido pela equipe ISA Saúde · Versão 2026

---

## 📋 Sobre o Projeto

Este é um checklist interativo desenvolvido para apoiar **auditores e gestores da ISA Saúde** na avaliação de prestadores de serviços de **Home Care (Atenção Domiciliar)**, verificando a conformidade com as principais normas e regulamentações brasileiras (ANVISA, ONA, CFM, COFEN, NRs).

O instrumento cobre **79 itens** distribuídos em **3 seções** e **17 subseções**, desde a documentação legal até a higienização, passando por farmácia, CME, manutenção e segurança do paciente.

---

## ✨ Funcionalidades

| Recurso | Descrição |
|---|---|
| ✅ **Checklist interativo** | Marque Sim / Não / N/A para cada item |
| 🔍 **Filtros e busca** | Filtre por status, tipo (R/M) ou pesquise por texto |
| 💾 **Salvamento automático** | Respostas salvas automaticamente no navegador |
| 🗂 **Arquivos salvos** | Gerencie múltiplos checklists arquivados |
| 📊 **Exportar Excel** | Gera `.xlsx` completo com resumo de conformidade |
| 🖨 **Impressão / PDF** | Layout otimizado para impressão |
| ✍️ **Assinatura digital** | Assine com mouse ou toque na tela |
| 📷 **QR Code** | Gera QR Code para compartilhar o link |
| 📈 **Progresso em tempo real** | Barra e percentual de conformidade atualizados |

---

## 🗂 Estrutura do Checklist

```
Seção 1 — Condições Organizacionais
  ├── 1.1 Gestão da Documentação Legal
  ├── 1.2 Processos Gerenciais
  ├── 1.3 Gestão da Segurança
  ├── 1.4 Certificações
  ├── 1.5 Serviço de Arquivo
  ├── 1.6 Núcleo de Segurança do Paciente
  ├── 1.7 Indicadores de Valor
  └── 1.8 Equipe Multiprofissional (EMAD)

Seção 2 — Atendimento ao Cliente
  ├── 2.1 Infraestrutura
  └── 2.2 Procedimentos

Seção 3 — Abastecimento e Apoio
  ├── 3.1 Gestão de Fornecedores e Compras
  ├── 3.2 Almoxarifado
  ├── 3.3 Farmácia
  ├── 3.4 CME — Central de Materiais Esterilizados
  ├── 3.5 Manutenção de Equipamentos
  ├── 3.6 Manutenção Predial
  └── 3.7 Higienização
```

---

## 🚀 Como Usar

### Acesso Online
Acesse diretamente pelo link:  
🔗 **[https://auditisa.netlify.app](https://auditisa.netlify.app)**

### Rodar Localmente
Não precisa instalar nada. Basta:

```bash
# 1. Clone o repositório
git clone https://github.com/seuusuario/isa-checklist.git

# 2. Abra o arquivo no navegador
# Dê dois cliques em index.html
```

---

## 🎨 Identidade Visual

O projeto segue a paleta oficial da **ISA Saúde**:

| Cor | Hex | Uso |
|---|---|---|
| 🩷 Rosa | `#ED1E79` | Destaques, botões primários, badges de seção |
| 🩵 Turquesa | `#00D2D4` | Bordas, progresso, subseções, logo |
| 🔵 Azul Institucional | `#233E72` | Header, cabeçalhos, textos |
| ⚪ Cinza Claro | `#F1F1F1` | Fundo geral, inputs |

---

## 📐 Tecnologias Utilizadas

- **HTML5 + CSS3 + JavaScript** puro — sem frameworks, sem instalação
- **[QRCode.js](https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js)** — geração de QR Code
- **[SheetJS (xlsx)](https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js)** — exportação para Excel
- **LocalStorage** — persistência de dados no navegador
- **Google Fonts** — Montserrat + Inter

---

## 📝 Referências Normativas

Os itens do checklist são baseados nas seguintes normas:

- **RDC Nº 11/2006** — Regulamento Técnico de Funcionamento de Serviços de AD
- **RDC Nº 36/2013** — Segurança do Paciente
- **RDC Nº 63/2011** — Boas Práticas para Serviços de Saúde
- **RDC Nº 222/2018** — Gerenciamento de Resíduos de Serviços de Saúde
- **RDC Nº 15/2012** — Esterilização de Produtos para Saúde
- **RDC Nº 67/2007** — Farmácia Hospitalar
- **NR 1, NR 7, NR 24** — Normas Regulamentadoras do Trabalho
- **ONA 2022** — Organização Nacional de Acreditação
- **Res. CFM Nº 2.218/2018** — Prontuário Eletrônico
- **ABNT NBR 14725:2023** — Saneantes

---

## ⚠️ Observação sobre os Dados Salvos

Os checklists são salvos no **localStorage do navegador** de cada dispositivo. Isso significa:
- ✅ Os dados ficam salvos mesmo fechando o navegador
- ✅ Não precisa de servidor ou banco de dados
- ⚠️ Os dados são **locais** — cada dispositivo tem seus próprios arquivos
- ⚠️ Limpar o cache do navegador apaga os dados salvos

---

## 📄 Licença

Este projeto é de uso interno da **ISA Saúde**.  
Todos os direitos reservados © 2026 ISA Saúde.

---

<div align="center">
  <strong>ISA Saúde</strong> · Inteligência em Saúde Assistencial · 2026
</div>
