backend:
  name: git-gateway
  branch: main   # troque para master se sua branch principal for master

media_folder: "uploads"
public_folder: "/uploads"

collections:
  - name: "pix"
    label: "Chave Pix"
    files:
      - file: "pix.json"
        label: "Configuração do Pix"
        name: "pix"
        fields:
          - { label: "Chave Pix", name: "chave_pix", widget: "string" }
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Admin</title>
    <script src="https://unpkg.com/netlify-cms@^2.0.0/dist/netlify-cms.js"></script>
  </head>
  <body>
  </body>
</html>
{
  "chave_pix": "meu-pix-inicial@banco.com"
}
