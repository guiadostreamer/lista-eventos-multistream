# Instalação e solução de problemas

## Requisitos
- Conta Streamlabs com acesso ao widget **Lista de Eventos**.
- Plataformas desejadas conectadas à conta Streamlabs e eventos habilitados no seletor.
- OBS Studio, Streamlabs Desktop ou outro software com fonte de navegador.

## Instalar do zero
1. No painel da **Lista de Eventos**, faça backup dos conteúdos existentes das abas HTML, CSS e JavaScript.
2. Habilite o tema com código personalizado.
3. Cole os três arquivos de `codigo/` nas abas correspondentes, **sem incluir o nome do arquivo ou blocos de Markdown**.
4. Selecione os eventos habilitados. Configure inicialmente **máximo de 5 eventos**, **Bits mínimos = 0** e **Kicks mínimos = 0** caso queira testar quantidades pequenas.
5. Salve as configurações; recarregue a fonte do navegador se preciso.
6. No OBS: adicione **Fonte de navegador**, informe a **URL do Widget** que aparece no Streamlabs. A URL é privada; **não a publique em prints/repositórios**.
7. Faça testes de diferentes plataformas. Não é necessário gastar dinheiro para provocar eventos monetizados.


## Problemas frequentes
- **Aparece “EVENTO”**: o Streamlabs pode não expor a plataforma na classe, tag ou atributos do template. O widget prefere rótulo neutro a inventar origem.
- **Evento com plataforma ou ação incorreta**: confirme que os três arquivos desta distribuição foram colados, salve e recarregue a fonte. Se persistir, registre uma captura e o tipo real no Feed de Atividades.
- **Evento não aparece**: revise contas conectadas, eventos marcados, limiares de Bits/Kicks e histórico, antes de suspeitar do tema.
- **Aparece cortado**: aumente largura/altura da fonte de navegador; a lista tem margens para a luz neon não ser recortada.
- **Nenhuma animação**: verifique configurações do Streamlabs e preferência do sistema por movimento reduzido.
- **Raids da Kick não aparecem**: a existência de raids na Kick não garante entrega pelo Streamlabs. A origem só terá cor da Kick se identificável no DOM.
- **Não funciona em arquivo HTML isolado**: o receptor de eventos pertence ao widget nativo Streamlabs, não a este tema.

## Restaurar
Cole novamente o backup das abas HTML, CSS e JavaScript e salve. A configuração de contas e recepção do Streamlabs não é alterada por este código.
