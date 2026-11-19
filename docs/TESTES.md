# Checklist de validação

## Teste visual básico
- [ ] Fonte carrega sem tela branca ou erro no console.
- [ ] Nomes e badges legíveis; luz neon sem cortes nas bordas.
- [ ] A lista respeita o limite selecionado no painel.
- [ ] Novas linhas entram com efeito suave; itens antigos saem.
- [ ] O painel continua registrando os eventos mesmo com tema personalizado.

## Casos por plataforma
- [ ] Twitch: seguir, inscrever-se, reinscrever-se, presente, Bits e raid.
- [ ] YouTube: inscrição, membro, presente, Super Chat, Super Sticker e Jewel Gift (quando disponíveis).
- [ ] Kick: seguir, inscrever-se, reinscrever-se, presentes e Kicks.
- [ ] Kick: raid **somente se** efetivamente recebida pelo Streamlabs.
- [ ] Facebook: seguir e estrelas; demais modalidades conforme painel da conta.
- [ ] Eventos sem origem explícita aparecem como `EVENTO` em vez de uma plataforma incorreta.

## Casos específicos de identificação
- [ ] `Kick` + `Seguiu` → Kick (verde), ação `Seguiu`.
- [ ] `Kick` + `Kicks` → Kick (verde), ação `Kicks`.
- [ ] `YouTube` + `Inscreveu-se` → YouTube (vermelho).
- [ ] `YouTube` + `Kicks` → Kick (verde), ação `Kicks`.
- [ ] `Jewel Gifts` → YouTube, nunca Kick.
- [ ] `Bits` → Twitch.
- [ ] `Super Chat` ou `Super Stickers` → YouTube.
- [ ] `Estrelas` / `Stars` → Facebook.
- [ ] `Raid` sem indicação explícita de plataforma → `EVENTO`.

## Para relatar um erro
Informe a versão, a ação testada, a plataforma selecionada no painel, a tag mostrada, uma captura da linha do widget e se foi teste simulado ou evento real. **Oculte a URL do widget, tokens, chaves e informações privadas.**
