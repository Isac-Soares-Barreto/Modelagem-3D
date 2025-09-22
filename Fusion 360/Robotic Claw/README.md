# 🦾 Robotic Claw - Garra Robótica

<div align="center">

![Fusion 360](https://img.shields.io/badge/Fusion%20360-FF6600?style=for-the-badge&logo=autodesk&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![License](https://img.shields.io/badge/License-Custom-yellow?style=for-the-badge)

**🤖 Uma garra robótica controlada por Arduino para automação de tarefas**

</div>

---

## 📋 Sobre o Projeto

Este é um projeto de **Garra Robótica** desenvolvido no **Fusion 360** com o objetivo de criar um sistema automatizado capaz de:

- 🎯 **Detectar** peças através de uma placa sensorial matricial 3x3
- 🤏 **Capturar** objetos com precisão
- 📦 **Armazenar** as peças em gavetas do tabuleiro
- 🔄 **Movimentar** com suavidade através de servomotores

> 💡 **Nota:** Este projeto foi desenvolvido para aprimorar habilidades em modelagem 3D e integração hardware-software!

---

## ⚙️ Especificações Técnicas

### 🔌 Eletrônica

| Componente | Quantidade | Função |
|--------------------------------|------------|-----------------------------------|
| **Arduino Nano** | 1x | Controlador principal |
| **Tower Pro MG90s 180°** | 4x | Servomotores para movimentação |
| **LM7805** | 4x | Reguladores de tensão 5V |
| **LM7809** | 1x | Regulador de tensão 9V |
| **Jack P4 PCI 2,5mm** | 1x | Entrada de alimentação |
| **Jumper de Passo** | 1x | Seletor de alimentação |
| **Barras de pinos Macho x Macho** | 7x | Conexões diversas |
| **Barras de pinos Macho x Fêmea** | 2x | Conexão do Arduino à placa ilhada |
| **Placa ilhada 5x7 cm** | 1x | Soldagem de componentes |
| **Placa de fenolite simples 10x10 cm** | 1x | Sensor matricial |
| **Diodo SR560** | 1x | Proteção de circuito |

### 🎛️ Sistema de Alimentação

- **🔋 Fonte Externa:** Quando o jumper está conectado.
- **💻 USB Arduino:** Quando o jumper está removido.

> ⚠️ **Importante:** Sempre remova o jumper ao alimentar o circuito via USB para evitar danos!

---

## 🏗️ Características do Design

### ✨ Diferenciais

- **📐 Design Paramétrico:** Alterações em medidas específicas redimensionam automaticamente todo o conjunto.
- **✂️ Fabricação Simplificada:** Peças otimizadas para corte em MDF com estilete ou a laser.
- **🔧 Juntas Funcionais:** Sistema de articulações simuladas para validar o movimento realista da garra.
- **🎯 Precisão:** Pinças dimensionadas para uma captura eficiente.

### 🛠️ Melhorias Implementadas

O design original das pinças (baseado em um modelo educativo da loja Saravati) foi extensivamente modificado para:

- Melhorar a aderência aos objetos
- Facilitar a fabricação
- Aumentar a durabilidade
- Aprimorar a estética

---

## 📦 Componentes 3D Utilizados

Agradecimentos especiais aos criadores dos modelos 3D que serviram como base para este projeto:

| Componente | Autor | Link |
|-------------------|----------------------|-------------------------------------------------------------------------------------|
| **Tower Pro MG90s** | Oleksii Pryimachenko | [GrabCAD](https://grabcad.com/library/tower-pro-mg90s-micro-servo-2) |
| **Arduino Nano** | Xmortium | [GrabCAD](https://grabcad.com/library/arduino-nano-v3-1) |
| **Jack P4 PCI 2,5mm** | Matheus Frasson | [GrabCAD](https://grabcad.com/library/jack-p4-pci-2-5mm-1) |
| **LM7809** | UNIT ELECTRONICS | [GrabCAD](https://grabcad.com/library/lm7809-1) |
| **LM7805** | UNIT ELECTRONICS | [GrabCAD](https://grabcad.com/library/regulador-lm7805-5v-1a-1) |

---

## 🎥 Canais de Referência

Agradecimentos especiais ao canal **Ponto Acadêmico (Profº Roberto Vichinsky)** por fornecer o material de uma placa matricial que serviu de inspiração para este projeto! 🎓

- **Link no YouTube:** [Como fazer um teclado matricial](https://www.youtube.com/watch?v=o9DZhZMqJrw)

---

## 📂 Estrutura do Repositório

Robotic Claw/
│	 ├── Robotic Claw Desenho.pdf # Arquivo das medições do projeto (desenvolvido automaticamente pelo Fusion 360)
│	 ├── Placa Sensorial.pdf # Arquivo da placa sensorial (placa matricial)
│    └── Robotic Claw.f3z # Arquivo principal do Fusion 360
├── 📁 Imagens/
│	 ├── Robotic 1.png
│	 ├── Robotic 2.png
│	 └── Robotic 3.png	
├── 📄 README.md # Este arquivo
└── 📄 LICENSE.md # Termos de uso

---

## 🚀 Como Usar

### 1️⃣ Modelagem 3D

- Abra o arquivo `.f3z` no Autodesk Fusion 360.
- Ajuste os parâmetros no menu `Modify > Change Parameters` conforme necessário.
- Exporte as peças para fabricação (corte a laser, impressão 3D, etc.).

### 2️⃣ Montagem Eletrônica

- Siga o esquemático para montar o circuito na placa ilhada.
- Configure o jumper de acordo com a fonte de alimentação escolhida.
- Conecte os servomotores nos pinos designados.

### 3️⃣ Programação

- Carregue o código no Arduino Nano.
- Ajuste os parâmetros de movimento e ângulos dos servos no código.
- Realize testes para calibrar a garra e os sensores.

---

## 🎯 Aplicações Possíveis

- 🏭 **Automação Industrial:** Linha de produção em pequena escala.
- 🎓 **Educação:** Ensino de robótica, programação e design CAD.
- 🔬 **Pesquisa:** Prototipagem de sistemas automatizados.
- 🎮 **Hobby:** Projetos pessoais de automação e DIY.

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

- 🐛 Reportar bugs e problemas
- 💡 Sugerir novas funcionalidades e melhorias
- 🔧 Enviar *pull requests* com suas alterações
- ⭐ Dar uma estrela no projeto se você gostou!

---

## 📜 Licença

Este projeto está sob uma licença customizada que permite uso livre com atribuição. Veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.

> 🚫 **Uso comercial direto (venda) do projeto não é permitido.**

---

## 👨‍💻 Autor

<div align="center">

**Isac Soares Barreto**

🔗 *Se você usar ou modificar este projeto, por favor dê os devidos créditos!*

</div>

---

<div align="center">

### ⭐ Se este projeto foi útil, considere dar uma estrela! ⭐

Feito com ❤️ e muito ☕

</div>
