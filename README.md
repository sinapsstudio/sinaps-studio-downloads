# Sinaps Studio
<img width="980" height="642" alt="{F69F42D7-179D-4592-A96E-636011C23654}" src="https://github.com/user-attachments/assets/07825d11-41bc-450e-bf20-ff98ac9a6288" />

**Integrated Model Environment (IME)**

A local-first desktop environment for exploring, developing, running, and understanding artificial intelligence — bringing models, datasets, multimodal workflows, agents, data tools, and observability into one workspace.

**[Download for Windows](https://github.com/sinapsstudio/sinaps-studio-downloads/releases) · [Sinaps Data website](https://www.sinapsdata.com.br/)**

**Languages:** English · Português · 简体中文

> **Distribution repository:** This repository is dedicated to official Sinaps Studio installers and release notes. It is **not** the application's source-code repository.

---

## English

### Explore AI in a single environment

Sinaps Studio connects to the **Hugging Face ecosystem**, giving users a way to discover **3M+ AI models** and **500K+ datasets** without having to download everything first. Catalog figures refer to the connected ecosystem, not to content bundled with the installer. Availability may vary by source, access permissions, and hardware.

### Main capabilities

- **Model & dataset catalogs:** discover, filter, preview, and download models and datasets to your projects.
- **Multimodal Canvas:** visual workflows for image, audio, and video model tasks.
- **Circuit Tracer & Trace Explorer:** inspect model weights and features; explore traces, dependencies, latency, and operation logs.
- **Data workspace:** integrated DBMS, SQL queries, dataset previews, and a catalog of **1,000+ compatible connectors**.
- **Local orchestration:** pipelines with manual execution, schedules, sensors, and automations, running in the user's environment.
- **AI Squads:** organize agents with tools, routing, memory, policies, and RAG configurations.
- **Community & collaboration:** share models, datasets, ideas, issues, training metrics, and results; connect through chat and communication features.
- **Local-first development:** workspace, files, hardware monitoring, and compatible local model execution; connected features require an internet connection.

### Download and install

1. Open the **[Releases page](https://github.com/sinapsstudio/sinaps-studio-downloads/releases)**.
2. Choose the latest published release and download the **Windows `.exe` installer** from **Assets**.
3. Run the installer and follow the on-screen instructions.

**Platform:** Windows x64. Actual CPU, RAM, storage, and GPU needs vary with the models and workloads selected. The availability of a particular release is shown on the Releases page.

**Security:** Download installers only from this repository or an official Sinaps Data channel. If the release publishes a SHA-256 checksum, verify the downloaded file in PowerShell:

```powershell
Get-FileHash "C:\path\to\SinapsStudioSetup.exe" -Algorithm SHA256
```

Compare the result with the checksum published in the release. Do not install files from untrusted mirrors.

### Support and project information

- Product and company: **[Sinaps Data](https://www.sinapsdata.com.br/)**
- Downloads and version history: **[GitHub Releases](https://github.com/sinapsstudio/sinaps-studio-downloads/releases)**
- Installation or distribution issues: **[GitHub Issues](https://github.com/sinapsstudio/sinaps-studio-downloads/issues)**, when enabled

The Hugging Face integration refers to ecosystem interoperability and does not imply an official commercial partnership or endorsement. This public downloads repository does not grant an open-source license for the desktop application.

---

## Português (Brasil)

O **Sinaps Studio** é um ambiente desktop de desenvolvimento e exploração de IA que reúne **modelos, datasets, Canvas multimodal, agentes, ferramentas de dados e observabilidade** em um único workspace.

Por meio da integração com o ecossistema **Hugging Face**, é possível descobrir **mais de 3 milhões de modelos de IA** e **mais de 500 mil datasets**. Esses números representam o ecossistema conectado, não arquivos incluídos no instalador.

### Funcionalidades

- **Modelos e datasets:** busca, filtros, pré-visualização e download para projetos.
- **Canvas multimodal:** fluxos visuais para modelos de imagem, áudio e vídeo.
- **Circuit Tracer e Trace Explorer:** inspeção de pesos, features, traces, dependências, latência e logs.
- **Dados e conectores:** DBMS integrado, consultas SQL e catálogo de **mais de 1.000 conectores compatíveis**.
- **Orquestração local:** pipelines com execução manual, agendamentos, sensores e automações.
- **Squads de agentes de IA:** ferramentas, roteamento, memória, políticas e configurações de RAG.
- **Comunidade:** publicações de modelos, datasets, ideias, problemas, métricas de treinamento e resultados, além de recursos de comunicação.

### Instalação

1. Abra **[Releases](https://github.com/sinapsstudio/sinaps-studio-downloads/releases)**.
2. Selecione a versão publicada mais recente e baixe o instalador **`.exe` para Windows x64** na área **Assets**.
3. Execute o arquivo e siga as instruções de instalação.

Os requisitos de hardware variam conforme os modelos e as tarefas utilizadas. O processamento e a orquestração locais não exigem que o usuário hospede o Dagster na nuvem. Recursos conectados, como catálogos públicos e comunidade, dependem de internet.

**Segurança:** obtenha o instalador somente neste repositório ou nos canais oficiais da Sinaps Data. Quando houver checksum SHA-256 na release, compare-o com o arquivo baixado usando `Get-FileHash` no PowerShell.

**Suporte:** [Sinaps Data](https://www.sinapsdata.com.br/) · [Releases](https://github.com/sinapsstudio/sinaps-studio-downloads/releases) · [Issues](https://github.com/sinapsstudio/sinaps-studio-downloads/issues) (se habilitado).

Este repositório é destinado à **distribuição de instaladores**, não à publicação do código-fonte. A integração com Hugging Face não representa, por si só, uma parceria comercial oficial.

---

## 简体中文

**Sinaps Studio** 是一款以本地工作环境为核心的 **AI 集成开发平台（IME）**，将模型、数据集、多模态 Canvas、AI 智能体、数据工具和可观测性整合在一起。

通过与 **Hugging Face 生态**的集成，用户可以探索 **300 万+ AI 模型**和 **50 万+ 数据集**。这些数字指的是连接的生态目录，而非安装包内置资源。

### 主要功能

- **模型与数据集：**搜索、筛选、预览及下载。
- **多模态 Canvas：**图像、音频和视频模型的可视化工作流。
- **Circuit Tracer 与 Trace Explorer：**查看权重、特征、执行轨迹、依赖、延迟和日志。
- **数据与连接器：**集成 DBMS、SQL 查询，以及 **1,000+** 个兼容连接器。
- **本地编排：**支持手动运行、定时任务、传感器和自动化的管道。
- **AI Squads：**提供工具、路由、记忆、策略和 RAG 配置。
- **社区：**分享模型、数据集、想法、问题、训练指标与结果。

### 下载

1. 打开 **[Releases 页面](https://github.com/sinapsstudio/sinaps-studio-downloads/releases)**。
2. 从最新发布版本的 **Assets** 下载 **Windows x64 `.exe` 安装程序**。
3. 运行安装程序并按照提示操作。

请仅从本仓库或 Sinaps Data 官方渠道下载安装程序。硬件要求取决于所选模型和工作负载。此仓库用于分发安装包，并非开源代码仓库。

---

© 2026 **Sinaps Data**. Sinaps Studio is a product of Sinaps Data.
