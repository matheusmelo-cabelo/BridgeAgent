# Instalação: BridgeAgent no Gemini CLI

Para utilizar o poder do BridgeAgent no seu Gemini CLI, siga as instruções abaixo para carregar o contexto na memória do agente.

## Opção 1: Carregamento por Diretório (Recomendado)

Aponte o Gemini CLI para a pasta raiz do framework. Isso permitirá que ele leia os manifestos, agentes e skills.

1.  No seu terminal, navegue até a pasta do projeto.
2.  Inicie o chat garantindo que os arquivos `.md` sejam lidos.
3.  Execute o comando inicial para ativar a inteligência:
    ```
    "Leia a pasta agents/ e core/ para entender suas novas diretrizes como BridgeAgent."
    ```

## Opção 2: Memória Permanente (DNA)

Você pode adicionar o caminho do BridgeAgent ao seu arquivo `~/.gemini/GEMINI.md` para que ele seja carregado em todas as sessões.

Adicione esta linha ao seu arquivo de memórias:
`- O framework BridgeAgent reside em /home/ghostwind/BridgeAgent/. Sempre que solicitado a criar um novo software, utilize as personas de agents/architect.md e siga o workflow em core/workflow.md.`

## Ativação Rápida

Sempre que iniciar um projeto novo, dê o seguinte comando ao Gemini:
> "Ativar BridgeAgent: [Descreva sua Vibe aqui]"

O Gemini assumirá o papel de **Architect**, consultará as diretrizes em `agents/architect.md` e iniciará o processo de entrevista.
