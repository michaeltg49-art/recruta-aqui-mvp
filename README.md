# Recruta Aqui — MVP de demonstração

Protótipo navegável de um portal de recrutamento e uma operação interna de RH. O projeto pode ser aberto diretamente pelo `index.html` ou publicado na Vercel com framework **Other** e diretório de saída `.`.

## Experiências

### Portal público
- Buscar vagas por cargo, empresa, área ou cidade.
- Abrir detalhes de uma oportunidade e iniciar candidatura.
- Criar perfil de demonstração.
- Responder o mapeamento de situações de trabalho.
- Ver sugestões de vagas com motivos explicáveis.

### Área do candidato
- Visão geral.
- Meu perfil e foto opcional.
- Vagas sugeridas.
- Candidaturas.
- Entrevistas.

### Gestão da Recruta Aqui
A área de gestão foi ampliada para representar a operação de uma empresa de recrutamento e seleção:

- Dashboard executivo com KPIs.
- Vagas e candidatos.
- Pipeline de seleção.
- Banco de talentos.
- Clientes e demandas.
- Agenda de entrevistas e reuniões.
- Indicadores de recrutamento e financeiro.
- Área **Meu negócio**, com dados da empresa, serviços/preços, financeiro, equipe/permissões, comunicação e preferências.

## Identidade e UX

A interface mantém a identidade azul/índigo da Recruta Aqui e foi redesenhada para uma experiência mais moderna, limpa e consistente, com hierarquia mais forte, cards, estados, microinterações e navegação própria para a operação de RH. O layout é responsivo para desktop, tablet e celular; em telas pequenas, a navegação lateral vira uma faixa horizontal e o menu principal é recolhível.

## Estado técnico atual

Esta é uma demonstração front-end. O estado fica em memória durante a visita e volta ao estado inicial ao recarregar. A autenticação ainda não é real, e nenhum dado é persistido em banco. Não use senhas reais.

A próxima evolução técnica é conectar a experiência a autenticação real, perfis e permissões por função, banco de dados, armazenamento seguro, candidaturas persistentes, agenda, notificações, contratos/clientes, financeiro e políticas de privacidade/LGPD. O mecanismo de correspondência deve manter critérios explícitos, revisão humana e evitar atributos sensíveis ou decisões automáticas sem explicação.

## Publicação

- Repositório: `michaeltg49-art/recruta-aqui-mvp`
- Branch principal: `main`
- Demo: `https://recruta-aqui-mvp.vercel.app/`
