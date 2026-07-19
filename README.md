# Entendendo o Real Time Operational System na prática

Materiais para apresentação, estudo e desenvolvimento prático com RTOS
(especificamente FreeRTOS), para entender como usar este sistema operacional
e construir soluções de baixo nível em sistemas embarcados.

## Site do workshop (GitHub Pages)

O site está em [`docs/`](docs/). É um template HTML/CSS estático — o visual é um
**design sample** e pode ser trocado depois editando os tokens em
[`docs/assets/css/main.css`](docs/assets/css/main.css).

| Caminho | Conteúdo |
| --- | --- |
| `docs/index.html` | Landing |
| `docs/modulos/` | Páginas de aula (exemplos) |
| `docs/exemplos/` | Componentes e snippets de referência |
| `docs/guia/como-usar.html` | Como adicionar páginas e publicar |

### Publicar

1. **Settings → Pages** no GitHub
2. Source: branch `main`, pasta `/docs`
3. Site em `https://<user-ou-org>.github.io/<repo>/`

### Pré-visualizar

```bash
cd docs
python3 -m http.server 8080
```

Abra http://localhost:8080

## Licença

Veja [LICENSE.md](LICENSE.md).
