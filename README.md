# ☁️ Nuvem e Seus Diferentes Tipos

Recentemente, tive a oportunidade de estudar sobre **computação em nuvem** na [DIO - Digital Innovation One](https://web.dio.me/track/bradesco-java-cloud-native), com foco nos modelos de **serviços em nuvem** como **PaaS**, **SaaS**, **IaaS** e nos **tipos de nuvem**: local, pública e híbrida.

A seguir, compartilho um resumo visual e explicativo sobre o que aprendi, ideal para quem está começando na área!

---

![Cloud Computing](https://brasilpaisdigital.com.br/wp-content/uploads/2023/10/nuvem-clouds.jpg)
> Fonte: [Brasil País Digital](https://brasilpaisdigital.com.br)

---

## 🌐 Tipos de Nuvem

| Tipo      | Vantagens                                               | Desvantagens                                           |
|-----------|---------------------------------------------------------|--------------------------------------------------------|
| **Local (On-Premises)** | Total controle sobre a infraestrutura <br> Maior privacidade e segurança | Altos custos com infraestrutura e manutenção <br> Requer equipe técnica dedicada |
| **Pública (Alugada)**   | Menor custo inicial <br> Alta escalabilidade <br> Manutenção feita pelo provedor | Menor controle sobre os dados <br> Depende da localização dos datacenters |
| **Híbrida**             | Equilíbrio entre custo e desempenho <br> Flexibilidade na alocação de recursos | Pode ser complexa de gerenciar <br> Requer integração entre ambientes |

---

## 🛠️ Modelos de Serviço

### 📦 SaaS — *Software as a Service*

> Você utiliza um software completo hospedado na nuvem.

📌 **Exemplo:** Microsoft Office 365, Google Workspace  
💡 **Como funciona:** Você paga por uma assinatura e usa diretamente via navegador ou app.

---

### ⚙️ IaaS — *Infrastructure as a Service*

> Você aluga a infraestrutura, como servidores e redes.

📌 **Exemplo:** Amazon EC2, Microsoft Azure VMs  
💡 **Como funciona:** Você monta seu próprio ambiente virtual na nuvem e só paga pelo que usar.

---

### 🏗️ PaaS — *Platform as a Service*

> Você desenvolve e hospeda aplicações sem se preocupar com o servidor.

📌 **Exemplo:** Heroku, Google App Engine  
💡 **Como funciona:** Ideal para desenvolvedores criarem apps sem gerenciar infraestrutura.

---

### 🖥️ DaaS — *Desktop as a Service*

> Computadores virtuais acessíveis de qualquer lugar.

📌 **Exemplo:** Azure Virtual Desktop, Amazon WorkSpaces  
💡 **Como funciona:** Excelente para empresas que querem mobilidade e segurança com desktops virtuais.

---

## ✅ Benefícios da Nuvem

- 🌍 Acesso global e remoto
- ⚡ Alta velocidade de transmissão
- 📈 Escalabilidade sob demanda
- 🛡️ Segurança gerenciada por grandes provedores

---

## ⚠️ Pontos de Atenção

- 🔐 A segurança local ainda é responsabilidade da empresa (no caso de nuvens híbridas ou locais)
- 💰 Custos podem escalar se não houver controle de uso
- 🌐 Latência pode variar dependendo da região do servidor

---

## 📊 Diagrama Ilustrativo

```mermaid
graph TD
    A[Usuário] --> B[Navegador/Dispositivo]
    B --> C[Internet]
    C --> D[Provedor de Nuvem]
    D -->|SaaS| E[Software]
    D -->|PaaS| F[Ambiente de Desenvolvimento]
    D -->|IaaS| G[Infraestrutura Virtual]
    D -->|DaaS| H[Desktop Virtual]
