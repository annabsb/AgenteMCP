# AgenteMCP
Criação de agente de IA usando o Model Context Protocol (MCP) em C#.


### Pré-requisitos

1. **Visual Studio Code**
   - Instalar de: <https://code.visualstudio.com/>

2. **.NET 9.0 SDK** (ou superior)

   ```powershell
   dotnet --version
   # Deve retornar 9.0 ou superior
   ```

   - Instalar de: <https://dotnet.microsoft.com/download>

3. **Node.js (v18+)** - para ferramentas auxiliares

   ```powershell
   node --version
   npm --version
   ```

   - Instalar de: <https://nodejs.org/>

4. **MCP Inspector** (para debug)

   ```powershell
   npm install -g @modelcontextprotocol/inspector
   ```

5. **GitHub Copilot CLI** (opcional)

   ```powershell
   npm install -g @github/copilot
   ```

### Extensões do VS Code Recomendadas

- C# Dev Kit
- C# (Microsoft)
- REST Client (para testar endpoints HTTP)

### Conhecimentos Prévios

- C# básico a intermediário
- Conceitos de async/await
- JSON básico
- Linha de comando (PowerShell)

### Estrutura do projeto

Agentes/
├── README.md (este arquivo)
├── src/
│   └── ServidorRemoto/        # Servidor MCP acessível via HTTP
│       └── HttpMcpServer/
├── configs/
│   ├── copilot-config.json
│   └── copilot-cli-config.json
└── docs/
    └── referencias.md

### Informações Importantes

** Versões utilizadas**
- .NET: 9.0
- ModelContextProtocol: 0.4.0-preview.1
- ModelContextProtocol.AspNetCore: 0.4.0-preview.1
- Microsoft.Extensions.Hosting: 9.0.9

### Feedback e Contribuições

Este é um projeto educacional em constante evolução. Seu feedback é essencial!
Entre em contato: annabeatrizbovo@gmail.com

**Como ajudar:**

- ⭐ Dê uma estrela no repositório se achou útil
- 🐛 Reporte bugs ou problemas
- 💡 Sugira melhorias
- 📝 Compartilhe sua experiência
- 🔧 Contribua com código
- 📖 Melhore a documentação

### Licença

Este workshop é disponibilizado sob licença MIT. Veja o arquivo LICENSE para mais detalhes.


