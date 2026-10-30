# Alquimia do Cheff: site estático

Este projeto é um único arquivo, `index.html`. Não há build nem dependências locais.

## Como publicar na Vercel (sem terminal)

1. Crie uma conta em vercel.com.
2. No painel, clique em **Add New > Project** e escolha arrastar a pasta, ou importe um repositório do GitHub com estes arquivos.
3. Em **Framework Preset**, deixe "Other". Deixe **Build Command** e **Output Directory** em branco.
4. Clique em **Deploy**.

## Antes de publicar de verdade

- [ ] Remover ou substituir a seção "Palavras doces" (depoimentos de exemplo).
- [ ] Preencher os campos `[PREENCHER]` em **Política de Privacidade** e **Termos de Encomenda** (razão social, CNPJ ou CPF, e-mail, prazos, sinal, formas de pagamento).
- [ ] Confirmar horário de funcionamento e incluir o link do iFood.
- [ ] Confirmar cardápio e preços com a loja.
- [ ] Testar o carrinho, o formulário de orçamento e os botões de WhatsApp no celular real.

## Como atualizar

- Com GitHub: altere o `index.html` no repositório, faça commit e a Vercel publica sozinha.
- Sem GitHub: substitua o `index.html` e envie a pasta novamente no painel.

## Domínio do cliente

Em **Settings > Domains** no projeto da Vercel, adicione o domínio (por exemplo, `alquimiadocheff.com.br`) e siga as instruções de DNS.
