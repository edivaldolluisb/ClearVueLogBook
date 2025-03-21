<!-- This Heuristic Evaluation Workbook replicates the one proposed by the
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Edivaldo Bonfim
**Date**: 08/03/2025
**Product**: Opticalia

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status

>     The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time.
>     - Does the design clearly communicate its state?
>     - Is feedback presented quickly after user actions?

| **Issue**                                                                             | **Severity** | Recommendation                                                                                                     |
| ------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------ |
| Não há feedback ao clicar no botão "Finalizar Compra" como convidado.                 | 4            | Adicionar uma mensagem clara informando que o usuário precisa se registrar ou fazer login para finalizar a compra. |
| Falta de feedback ao tentar adicionar um item ao carrinho (como convidado ou logado). | 4            | Fornecer uma mensagem de erro clara explicando por que o item não pode ser adicionado ao carrinho.                 |
|                                                                                       |

# 2 Match Between System and The Real World

>     The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order.
>     - Will user be familiar with the terminology used in the design?
>     - Do the design’s controls follow real-world conventions?

| **Issue**                                                            | **Severity** | Recommendation                                                                               |
| -------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------- |
| Problemas de tradução para espanhol (frases e palavras em espanhol). | 3            | Revisar e corrigir as traduções para garantir consistência no idioma escolhido pelo usuário. |
|                                                                      |

# 3 User Control and Freedom

>     Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process.
>     - Does the design allow users to go back a step in the process?
>     - Are exit links easily discoverable?
>     - Can users easily cancel an action?
>     - Is Undo and Redo supported?

| **Issue**                                                       | **Severity** | Recommendation                                                                                         |
| --------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------ |
| Não é possível adicionar itens ao carrinho como convidado.      | 4            | Permitir que usuários convidados adicionem itens ao carrinho, solicitando registro apenas no checkout. |
|                                                                 |
| Processo de remoção de conta é interno (precisa enviar e-mail). | 3            | Adicionar uma opção direta no painel do usuário para excluir a conta.                                  |
|                                                                 |

# 4 Consistency and Standards

>     Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions.
>     - Does the design follow industry conventions?
>     - Are visual treatments used consistently throughout the design?

| **Issue**                                                            | **Severity** | Recommendation                                                                |
| -------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------- |
| Botão "Adicionar ao Carrinho" não funciona.                          | 4            | Corrigir o funcionamento do botão e garantir que ele execute a ação esperada. |
|                                                                      |
| Botão "Continuar como Convidado" não explica os limites dessa opção. | 3            | Adicionar uma explicação clara sobre as limitações de comprar como convidado. |
|                                                                      |

# 5 Error Prevention

>     Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action.
>     - Does the design prevent slips by using helpful constraints?
>     - Does the design warn users before they perform risky actions?

| **Issue**                                                              | **Severity** | Recommendation                                                                            |
| ---------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------- |
| Não é possível adicionar produtos ao carrinho, mesmo após fazer login. | 4            | Corrigir o problema técnico e garantir que o carrinho funcione corretamente após o login. |
|                                                                        |

# 6 Recognition Rather than Recall

>     Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed.
>     - Does the design keep important information visible, so that users do not have to memorize it?
>     - Does the design offer help in-context?

| **Issue**                                              | **Severity** | Recommendation                                                                         |
| ------------------------------------------------------ | ------------ | -------------------------------------------------------------------------------------- |
| Para criar uma conta, é necessário adicionar uma loja. | 3            | Simplificar o processo de registro, removendo a obrigatoriedade de adicionar uma loja. |
|                                                        |

# 7 Flexibility and Efficiency of Use

>     Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions.
>     - Does the design provide accelerators like keyboard shortcuts and touch gestures?
>     - Is content and funtionality personalized or customized for individual users?

| **Issue**                                                   | **Severity** | Recommendation                                                                          |
| ----------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------- |
| Processo de registro é complexo (exige adicionar uma loja). | 3            | Oferecer um processo de registro simplificado para usuários que desejam apenas comprar. |
|                                                             |

# 8 Aesthetic and Minimalist Design

>     Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility.
>     - Is the visual design and content focused on the essentials?
>     - Have all distracting, unnescessary elements been removed?

| **Issue**                                                        | **Severity** | Recommendation                                                                                    |
| ---------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------- |
| Interface pode ser confusa devido a problemas de funcionalidade. | 2            | Simplificar a interface e garantir que todas as funcionalidades estejam funcionando corretamente. |
|                                                                  |

# 9 Help Users Recognize, Diagnose, and Recover from Errors

>     Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution.
>     - Does the design use traditional error message visuals, like bold, red text?
>     - Does the design offer a solution that solves the error immediately?

| **Issue**                                                                | **Severity** | Recommendation                                                                 |
| ------------------------------------------------------------------------ | ------------ | ------------------------------------------------------------------------------ |
| Falta de mensagens de erro claras ao tentar adicionar itens ao carrinho. | 4            | Fornecer mensagens de erro específicas e orientações para resolver o problema. |
|                                                                          |

# 10 Help and Documentation

>     It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks.
>     - Is help documentation easy to search?
>     - Is help provided in context right at the moment when the user requires it?

| **Issue**                                                 | **Severity** | Recommendation                                                    |
| --------------------------------------------------------- | ------------ | ----------------------------------------------------------------- |
| Falta de suporte contextual durante o processo de compra. | 3            | Adicionar uma seção de ajuda ou FAQ acessível durante o checkout. |
|                                                           |
| Another thing                                             | 4            |                                                                   |
