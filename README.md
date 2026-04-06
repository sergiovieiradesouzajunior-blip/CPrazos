# CPrazos - Calculadora de Prazos Jurídicos Brasileiros

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Ferramenta web para cálculo de prazos jurídicos e administrativos brasileiros, desenvolvida conforme as regras do CPC/2015, CPP, Código Civil e Lei 9.784/99.

## 🚀 Funcionalidades

### Regimes de Contagem Implementados

| Regime | Base Legal | Tipo de Contagem | Dia Inicial | Dia Final | Prorrogação |
|--------|------------|------------------|-------------|-----------|-------------|
| **CPC/2015** | Art. 219 | Dias Úteis | Exclui | Inclui | Sim |
| **CPP** | Art. 798 | Dias Corridos | Inclui | Inclui | Não |
| **Código Civil** | Art. 132 | Dias Corridos | Exclui | Inclui | Sim |
| **Penal Material** | CP Art. 10 | Dias Corridos | Inclui | Inclui | Não |
| **Lei 9.784/99** | Art. 66 | Dias Corridos | Exclui | Inclui | Sim |

### Principais Recursos

- ✅ **Cálculo em múltiplas fases** - Configure várias fases encadeadas
- ✅ **Unidades flexíveis** - Dias, Horas, Meses ou Anos
- ✅ **Gestão de feriados** - Feriados nacionais pré-cadastrados
- ✅ **Suspensões customizáveis** - Adicione recessos e suspensões de tribunal
- ✅ **Tema claro/escuro** - Interface adaptável
- ✅ **100% offline** - Funciona sem internet (Single File Application)
- ✅ **Responsivo** - Mobile-first design
- ✅ **Exportação** - Imprima ou salve como PDF

## 📋 Como Usar

### 1. Acesse a aplicação
Abra o arquivo `index.html` em qualquer navegador moderno.

### 2. Configure o cálculo
- Selecione o **âmbito** (Judicial ou Administrativo)
- Escolha o **regime de contagem**
- Defina a **unidade de medida**
- Opte por **Data Única** ou **Múltiplas Fases**

### 3. Informe os prazos
- Digite o valor do prazo
- Selecione se são dias úteis ou corridos
- Informe a data de início

### 4. Visualize os resultados
- Tabela com todas as datas calculadas
- Indicação de prorrogações automáticas
- Status do prazo (vencido, próximo, futuro)

## ⚙️ Gestão de Feriados e Suspensões

Clique no ícone de engrenagem (⚙️) no cabeçalho para:

- **Adicionar suspensões** - Recessos judiciários, portarias de suspensão
- **Visualizar feriados** - Lista de feriados nacionais considerados
- Os dados são salvos no navegador (localStorage)

## 🔗 Integração com API

A aplicação busca automaticamente os feriados da [BrasilAPI](https://brasilapi.com.br/) ao carregar. Em caso de falha, utiliza os feriados fixos pré-cadastrados como fallback.

## 📱 Compatibilidade

- Google Chrome (recomendado)
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

## 🛠️ Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Variáveis CSS, Flexbox, Grid, animações
- **JavaScript ES6+** - Módulos, async/await, localStorage

## 📄 Licença

Este projeto é de uso livre para fins educacionais e profissionais.

## 👨‍💻 Desenvolvimento

Desenvolvido com base nas melhores práticas de Legal Tech, seguindo rigorosamente a legislação processual brasileira.

---

**⚠️ Aviso Legal**: Esta ferramenta é um auxílio para cálculo de prazos. Sempre confirme os resultados com a legislação aplicável e consulte um profissional do Direito para casos específicos.
