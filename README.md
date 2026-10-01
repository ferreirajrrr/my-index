# my-index

Biblioteca de sites de referência para compor nossos projetos de front end.

## Como funciona

Todos os links ficam no arquivo `sites.json`. Cada site tem este formato:

```json
{
  "name": "Nome do site",
  "url": "https://exemplo.com",
  "description": "Uma frase dizendo para que serve",
  "category": "componentes-ui",
  "tags": ["react", "tailwind"],
  "added": "2026-10-01"
}
```

## Categorias

| Categoria | O que entra aqui |
|---|---|
| `inspiracao` | Galerias e sites bonitos para se inspirar |
| `componentes-ui` | Bibliotecas de componentes prontos |
| `animacoes-e-3d` | Bibliotecas de animação, motion e 3D |
| `tipografia` | Fontes e recursos de tipografia |
| `cores-e-design` | Paletas, gradientes, ferramentas de design |
| `ferramentas` | Utilitários e apps para o dia a dia |
| `templates` | Templates e projetos base |
| `aprendizado` | Cursos, docs e tutoriais |
| `outros` | O que não se encaixa nas anteriores |

## Como usar nos projetos

Antes de começar qualquer projeto de front end, consulte esta biblioteca:

1. **Direção visual**: navegue por `inspiracao` e `tipografia` para definir o estilo.
2. **Estrutura**: procure em `componentes-ui` antes de construir um componente do zero.
3. **Movimento**: escolha a biblioteca de `animacoes-e-3d` que combina com a stack (Motion ou React Spring em React, GSAP para animações de scroll complexas, Three.js para 3D).
