# OpenManus - Instalação Personalizada para eltonh9

## 🎉 Instalação Concluída!

O OpenManus foi instalado com sucesso em seu sistema. Este é um agente de IA autônomo de código aberto que pode automatizar diversas tarefas.

## 🚀 Como Executar

### Método 1: Script Automático (Recomendado)
```bash
./start_openmanus.sh
```

### Método 2: Execução Manual
```bash
# 1. Ativar ambiente virtual
source .venv/bin/activate

# 2. Executar OpenManus
python main.py --prompt "Sua mensagem aqui"
```

## ⚙️ Configuração

1. **Configure suas chaves de API** em `config/config.toml`
2. 2. **Provedores suportados:** OpenAI, Anthropic, Ollama, Google Gemini
  
   3. ## 🎯 Exemplos de Uso
  
   4. ```bash
      # Análise de dados
      python main.py --prompt "Analise os dados do arquivo vendas.csv"

      # Criação de código
      python main.py --prompt "Crie um site simples em HTML"
      ```

      ---
      **Instalado e configurado por Manus AI Assistant**
