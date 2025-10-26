# Electema - Serviço de Eletricista Residencial

![Banner Electema](https://placehold.co/1200x300/1053D4/CAEE5A/png?text=Electema+-+O+Seu+Eletricista+Residencial)

## ⚡ Visão Geral

O projeto **Electema** é um template de página inicial (landing page) moderno e responsivo, focado em promover serviços de eletricista residencial. A página destaca os serviços oferecidos, o processo de contratação (Como Funciona), os diferenciais da empresa (Por Que Nos Escolher), a equipe de técnicos, depoimentos de clientes e a área de atuação.

Esta aplicação é construída puramente com **HTML** e **CSS**, seguindo uma estrutura modular e utilizando um design vibrante.

## ✨ Recursos

- **Design Responsivo:** O layout se adapta a diferentes tamanhos de tela.
- **Navegação Clara:** Cabeçalho com informações de contato e menu de navegação principal.
- **Seções de Destaque:**
  - **Herói (Container Principal):** Mensagem de impacto e chamada para ação.
  - **Clientes:** Demonstração de confiança com logotipos de clientes.
  - **Como Funciona:** Passos simples para contratar o serviço.
  - **Por Que Nos Escolher (Why Us):** Destaque para experiência e satisfação do cliente.
  - **Nossos Técnicos (Meet):** Apresentação dos profissionais.
  - **Depoimentos (Testimonial):** Prova social com avaliações de clientes.
  - **Localização (Location):** Indicação das áreas de operação.
- **Rodapé Completo:** Links de navegação, recursos, redes sociais e formulário de inscrição.

## 🚀 Como Executar Localmente

Siga estas instruções para configurar e executar o projeto em seu ambiente de desenvolvimento.

### Pré-requisitos

Você só precisa de um **navegador web** (como Chrome, Firefox, Edge, etc.).

### Instalação

1.  **Clone o repositório** para sua máquina local:

    ```bash
    git clone [https://github.com/SeuUsuario/Electema.git](https://github.com/SeuUsuario/Electema.git)
    ```

    _(Substitua `SeuUsuario` pelo seu usuário ou o caminho correto do repositório)_

2.  **Acesse a pasta do projeto:**

    ```bash
    cd Electema
    ```

3.  **Abra o arquivo `index.html`** no seu navegador de preferência.

    Alternativamente, se você usa o VS Code, pode utilizar a extensão **Live Server** para rodar a aplicação em um servidor local com recarregamento automático.

## 📁 Estrutura do Projeto

O projeto segue uma estrutura de arquivos simples e direta:

Electema/ ├── index.html # O arquivo principal da landing page. ├── styles.css # O arquivo CSS com todos os estilos. └── imagens/ # Pasta contendo todas as imagens do projeto (logos, ícones, fotos, etc.). ├── Logo (1).png ├── twitter (1).png ├── facebook (1).png ├── ... (outras imagens)

## 🛠️ Tecnologias Utilizadas

| Tecnologia       | Descrição                                                       |
| :--------------- | :-------------------------------------------------------------- |
| **HTML5**        | Estrutura semântica e acessível da página.                      |
| **CSS3**         | Estilização completa, incluindo responsividade e variáveis CSS. |
| **Google Fonts** | Uso das fontes `Inter Tight` e `Inter`.                         |

### Variáveis CSS

O arquivo `styles.css` utiliza variáveis CSS para facilitar a manutenção das cores:

```css
:root {
    --button-principal: #caee5a;  /* Amarelo/Verde para botões de destaque */
    --bg-topo: #f2f4f8;           /* Fundo do cabeçalho superior */
    --bg-principal: #1053d4;      /* Azul principal */
    --color-principal: #ffffff;   /* Cor primária para texto (branco) */
    /* ... outras variáveis de cor ... */
}
📝 Acessibilidade (Sugestão de Melhoria)
O código HTML já incorpora alguns atributos de acessibilidade importantes:

lang="pt-BR": Define o idioma da página.

aria-label: Utilizado para fornecer um rótulo acessível a elementos como a navegação de contatos (<div aria-label="Navegação de Contatos">).

Observação: Certifique-se de que todas as tags <img> possuam o atributo alt com uma descrição significativa para usuários de leitores de tela. O seu código já está fazendo isso de forma excelente!

🤝 Contribuições
Contribuições são sempre bem-vindas! Se você tiver sugestões para melhorar o código, adicionar recursos ou corrigir bugs, sinta-se à vontade para:

Fazer um Fork do projeto.

Criar uma Branch para sua feature (git checkout -b feature/melhoria).

Fazer o Commit das suas mudanças (git commit -m 'feat: Adiciona nova funcionalidade').

Fazer o Push para a Branch (git push origin feature/melhoria).

Abrir um Pull Request.

Desenvolvido por: Paulo Borges (DevBorges8) - Baseado no template Tokotema.
```
