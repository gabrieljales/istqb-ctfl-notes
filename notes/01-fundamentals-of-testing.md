#  1. Fundamentos de teste

- **Teste de software:** Conjunto de atividades para descobrir defeitos e avaliar a qualidade dos Artefatos de Software.
    - **Artefatos de software:** São os objetos de teste.
        - **Objetos de teste:** Artefatos de software quando estão sendo testados.

- Os testes de software **verificam** e **validam** os objetos de teste.
    - **Verificação:** Verifica se o sistema atende aos requisitos especificados. "O sistema está construído corretamente?"
    - **Validação:** Checa se o sistema atende as necessidades dos usuários e outros stakeholders em ambiente operacional. "O sistema é útil e eficaz?"
    ```
    Exemplo para compreender melhor Verificação vs Validação (Busca em um E-Commerce):

        - Requisito: Ao digitar o termo e clicar em "Buscar", o sistema deve retornar itens que contenham a palavra buscada no seu título.

        --> Verificação: Você testa, digita "camisa" e o sistema retorna 50 itens. A verificação passou, a regra foi seguida.
        --> Validação: Na verdade, o usuário quer encontrar camisas azuis e sejam tamanho "M". Se a busca é só por título, sem filtros e tamanho ou cor, ela não atende a necessidade real do usuário. Portanto, nesse caso a validação falhou!
    ```

- Os testes podem ser:
    - **Dinâmicos:**
        - Envolve a execução do  software;
        - Usam diferentes tipos de técnicas de testes e abordagens de teste para derivar casos de teste;
        - Objetivo: Validar comportamento do software, medir performance e garantir que as funcionalidades atendam às necessidades do usuário;
        - Exemplos:
            - Testes unitários;
            - Testes de integração;
            - Testes de API;
            - Testes de Interface (UI).
    - **Estáticos:**
        - Não envolve a execução do software;
        - Foca em revisões e análises estáticas de documentos e do código fonte para encontrar **defeitos** ANTES do programa rodar;
        - Objetivo: Encontrar defeitos na lógica, inconsistências em requisitos ou violações de padrões de código;
        - Exemplos:
            - Revisão de requisitos;
            - Code Review;
            - Análise estática por ferramentas (Exemplo: SonarQube).

- Os testes não são apenas uma atividade técnica! Eles precisam ser:
    - Planejados: Objetivos e abordagem (estratégia);
    - Estimados: Prever esforço, tempo e recursos necessários;
    - Monitorados: Comparar progresso real com o planejado;
    - Controlados: Tomar ações corretivas baseadas no monitoramento;
    - Gerenciados: Coordenação das atividades e interface com o time.

- O teste é, em grande parte, uma atividade **intelectual**. Exige que o testador tenha:
    - Conhecimento especializado;
    - Use habilidades analíticas;
    - Aplique pensamento crítico e sistêmico.

- A norma **ISO/IEC/IEEE 29119-1** fornece mais informações sobre conceitos de teste de software.

## 1.1.1 Objetivos do teste