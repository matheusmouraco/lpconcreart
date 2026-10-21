# Concreart — Landing Page de Lançamento

Código-fonte do site de lançamento da **Concreart** (fábrica de concreto de alto padrão, região de Campinas/SP), apresentando os produtos **Régua de Concreto** e **Piso Drenante**.

## Sobre

- Site estático de página única (HTML + CSS + JavaScript, sem dependências ou build).
- Objetivo: gerar contato e orçamento via WhatsApp.
- Fonte oficial da marca: ID Grotesk.

## Estrutura

```
concreart-lp/
├── index.html          # O site completo (HTML + CSS + JS)
└── assets/
    ├── fonts/          # Fonte oficial ID Grotesk
    └── img/            # Fotos dos produtos, hero e galeria
```

## Como rodar localmente

Por ser um site estático, basta abrir o `index.html` no navegador. Para servir em um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Configuração rápida

Os dados de contato ficam centralizados na constante `CONFIG`, no topo do bloco `<script>` em `index.html`:

```js
const CONFIG = {
  whatsapp: "551939094999",
  email: "contato@concreart.com.br",
  instagram: "https://www.instagram.com/concreartmolduras/",
  site: "https://concreart.com.br",
};
```

## Publicação

O site está publicado via Vercel.
