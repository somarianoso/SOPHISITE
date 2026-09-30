# SOPHISITE

Currículo e portfólio pessoal de Sophia Soares Mariano.

## Site

O site será publicado em https://somarianoso.github.io/SOPHISITE/ pelo GitHub Pages. Para habilitar a publicação, selecione **Settings > Pages > Build and deployment > Source > GitHub Actions** no repositório. Cada atualização em `main` inicia um novo deploy.

## Prévia local

Na raiz do repositório, execute:

```sh
python3 -m http.server 8000
```

Depois, acesse http://localhost:8000.

## Currículos em PDF

Os arquivos locais ficam em `curriculos/`, diretório ignorado pelo Git. Eles não são enviados ao GitHub Pages; use o contato por e-mail no site para solicitar uma cópia.

## Segurança

O site é estático, sem servidor de aplicação ou formulários, e usa uma Content Security Policy restritiva. Isso reduz a superfície de ataque; nenhuma configuração impede toda indisponibilidade ou ataque de negação de serviço.
