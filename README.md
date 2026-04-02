# Ficha de Atendimento Marta v.2

Este aplicativo foi desenvolvido para o preenchimento e impressão de fichas de atendimento para terapias integrativas e numerologia.

## Funcionalidades

-   **Preenchimento Digital:** Campos para dados do cliente, numerologia, leitura energética e chakras.
-   **Impressão de Ficha Preenchida:** Gere um PDF formatado com todos os dados inseridos.
-   **Impressão de Ficha em Branco:** Gere um PDF limpo para preenchimento manual.
-   **Limpeza de Campos:** Botão para resetar o formulário.
-   **Design Responsivo:** Funciona em dispositivos móveis e desktops.

## Tecnologias Utilizadas

-   **React 19**
-   **Vite**
-   **Tailwind CSS**
-   **Lucide React** (Ícones)
-   **Motion** (Animações)
-   **Google Gemini API** (Opcional, para funcionalidades futuras)

## Como Usar Localmente

1.  Clone o repositório:
    ```bash
    git clone <url-do-repositorio>
    ```
2.  Instale as dependências:
    ```bash
    npm install
    ```
3.  Inicie o servidor de desenvolvimento:
    ```bash
    npm run dev
    ```
4.  Acesse `http://localhost:3000` no seu navegador.

## Implantação no GitHub Pages

Este projeto está configurado para ser implantado automaticamente no GitHub Pages via GitHub Actions.

1.  Vá para as configurações do seu repositório no GitHub.
2.  Navegue até **Pages**.
3.  Em **Build and deployment**, selecione **GitHub Actions** como fonte.
4.  O workflow em `.github/workflows/deploy.yml` cuidará do resto a cada push na branch `main`.

### Configuração de Segredos (Opcional)

Se você estiver usando a API do Gemini, adicione o segredo `GEMINI_API_KEY` nas configurações do repositório (**Settings > Secrets and variables > Actions**).

## Instruções para Impressão

Para garantir a melhor qualidade ao salvar como PDF ou imprimir:
-   Certifique-se de marcar a opção **"Gráficos de plano de fundo"** no menu de impressão.
-   Selecione **"Ajustar à página"** ou **"Margens: Nenhuma"** para manter o layout original.

---
Desenvolvido com ❤️ para terapias integrativas.
