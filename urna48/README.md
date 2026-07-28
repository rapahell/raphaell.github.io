# Urna48 — Site institucional

Landing page do serviço Urna48: sites de campanha para deputado estadual e federal, no ar em 48 horas.

## Estrutura

- `index.html` — landing page principal
- `termos-de-uso.html` — termos de uso e condições de contratação
- `politica-de-privacidade.html` — política de privacidade (LGPD)
- `_redirects` — regras de rota do Cloudflare Pages

## Hospedagem

Publicado via Cloudflare Pages, conectado a este repositório.
Cada commit na branch principal republica o site automaticamente.

## Domínio

urna48.com.br — registrado no Registro.br, DNS gerenciado pela Cloudflare.

## Pendências antes de divulgar

- [ ] Substituir o número de WhatsApp placeholder (5562000000000)
- [ ] Preencher telefone e data nos documentos legais
- [ ] Revisão dos documentos por advogado
- [ ] Instalar o sistema de briefing (Supabase + Resend)
- [ ] Conectar o webhook da Kiwify ao sistema
