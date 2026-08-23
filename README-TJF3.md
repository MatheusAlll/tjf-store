# TJF 3.0

Catálogo conectado ao Supabase.

- `tjf3.html`: catálogo público, leitura dos produtos ativos no PostgreSQL.
- `admin.html`: painel de cadastro, edição e exclusão.
- Supabase `products`: fonte única dos produtos.
- Supabase Storage `products`: armazenamento das novas imagens.
- Edge Function `admin-products`: operações administrativas e upload de imagens.

As imagens dos produtos migrados continuam usando os arquivos existentes no GitHub Pages. Novas imagens são enviadas ao Supabase Storage.
