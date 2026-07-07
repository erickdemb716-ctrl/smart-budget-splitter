# Smart Budget Splitter Mobile

O app esta pronto como PWA instalavel para Android e iOS, mas ele precisa ser aberto por um endereco web. Abrir pelo caminho `C:/Users/.../smart-budget-splitter.html` e apenas abrir um arquivo local; assim o navegador nao mostra a opcao correta de instalar/adicionar a tela inicial.

## Jeito certo de testar no computador

Use a URL local:

`http://127.0.0.1:8765/smart-budget-splitter.html`

Esse endereco funciona no proprio computador.

## Para instalar no celular

O celular precisa abrir um link web acessivel por ele. As melhores opcoes sao:

1. Publicar a pasta `outputs` em um hospedador com HTTPS, como Netlify, Vercel ou GitHub Pages.
2. Abrir o link publicado no Chrome Android ou Safari iPhone.
3. Usar "Instalar app" no Android ou "Adicionar a Tela de Inicio" no iPhone.

## Observacao importante

Para aparecer como app instalavel completo, Android/Chrome exige HTTPS ou localhost. Como o celular nao acessa o `localhost` do computador, o ideal e publicar em HTTPS.

## Publicar nas lojas

Para Google Play e App Store, use esta mesma base com Capacitor. A publicacao exige conta de desenvolvedor, certificados e build nativo para Android/iOS.
