# Anexos na cloud — JÁ CONFIGURADO ✅

A cloud está ligada e a funcionar. Não tens de fazer nada.

## O que está montado
- **Projeto Supabase:** `clvsn-calendar` (ref `dgppjyumexrwilkekety`), região London (eu-west-2),
  na tua org Supabase ("Rodrigo"). Plano grátis — 0€/mês.
- **Bucket público:** `calendar-files` (até 50MB por ficheiro), com permissões de
  leitura / upload / remoção.
- **Ligação no calendário:** `src_index.html` → `const SUPA = { ... }` já tem o URL
  e a chave pública corretos.
- Testado de ponta a ponta (upload + leitura pública + remoção): OK.

## Como usar
Abre um post → secção **Anexos / Ficheiros** → arrasta ou escolhe ficheiros → **Guardar**.
Os anexos vão para a nuvem (aparecem com ☁), ficam acessíveis em qualquer PC e a
toda a equipa.

## Chaves
- URL: `https://dgppjyumexrwilkekety.supabase.co`
- Chave pública (anon/publishable, pode ir no HTML): `sb_publishable_buiS1_ZQlQ9ykslx1nuy_A_-CY2T4YN`
- A chave **secreta / service_role** NUNCA pode ir no HTML. (Não está, e não deve estar.)

## Notas
- As permissões são permissivas (qualquer pessoa com o site pode enviar/apagar).
  Chega para a PAP. Para produção a sério: ligar Supabase Auth e restringir por utilizador.
- Painel do projeto: https://supabase.com/dashboard/project/dgppjyumexrwilkekety
