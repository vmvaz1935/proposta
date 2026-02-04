# Instruções de Uso - Landing Page

## Como Abrir no Navegador

1. **Localmente:**
   - Abra o arquivo `index.html` diretamente no seu navegador (duplo clique)
   - Ou arraste o arquivo para uma janela do navegador
   - Funciona em qualquer navegador moderno (Chrome, Firefox, Edge, Safari)

2. **Navegação:**
   - Use o menu de navegação fixo no topo para ir direto às seções
   - Role a página para navegar pelo conteúdo
   - Clique nos botões "Agendar Conversa" para ir direto ao formulário de contato

## Como Publicar Online

### Opção 1: Vercel (Recomendado - Mais Rápido)

1. Acesse [vercel.com](https://vercel.com) e faça login (pode usar GitHub)
2. Clique em "Add New Project"
3. Arraste a pasta com os arquivos (`index.html`, `logosuperior.webp`, `logoinferior.webp`)
4. Clique em "Deploy"
5. Pronto! Você receberá um link público (ex: `seu-projeto.vercel.app`)

### Opção 2: Netlify

1. Acesse [netlify.com](https://netlify.com) e faça login
2. Arraste a pasta com os arquivos para a área de deploy
3. O site será publicado automaticamente
4. Você receberá um link público (ex: `seu-projeto.netlify.app`)

### Opção 3: GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos (`index.html` e as imagens)
3. Vá em Settings → Pages
4. Selecione a branch `main` e a pasta `/root`
5. Salve e aguarde alguns minutos
6. Seu site estará em `seu-usuario.github.io/nome-do-repositorio`

### Opção 4: Qualquer Servidor Web

- Faça upload dos arquivos para qualquer servidor web (FTP, cPanel, etc.)
- Certifique-se de que `index.html` está na raiz ou ajuste o caminho
- As imagens devem estar na mesma pasta ou ajuste os caminhos no HTML

## Arquivos Necessários

Certifique-se de incluir todos estes arquivos ao publicar:

- `index.html` (arquivo principal da landing page)
- `logosuperior.webp` (logo superior - aparece no header)
- `logoinferior.webp` (logo inferior - aparece no footer)

## Características da Landing Page

✅ **Design Responsivo** - Funciona perfeitamente em desktop, tablet e celular
✅ **Navegação Fixa** - Menu sempre visível no topo
✅ **Scroll Suave** - Transições suaves entre seções
✅ **SEO Friendly** - Estrutura otimizada para mecanismos de busca
✅ **Performance** - Carregamento rápido, sem dependências externas pesadas

## Personalização

Se quiser alterar cores, textos ou estrutura, edite o arquivo `index.html` diretamente. 
O CSS está embutido no arquivo, facilitando ajustes.

### Cores Principais (no CSS):
- `--primary-color`: #1a365d (azul escuro)
- `--secondary-color`: #2c5282 (azul médio)
- `--accent-color`: #3182ce (azul claro)

### Seções da Landing Page:
1. Hero (cabeçalho principal)
2. Para Quem É
3. Contexto
4. Problema → Solução
5. Documentos Avulsos (tabelas)
6. Pacotes Fechados
7. Planos Mensais
8. Módulo B2B2C
9. Como Funciona
10. CTA / Contato
11. Footer

## Dicas de Otimização

- **Imagens**: Certifique-se de que as imagens estão otimizadas (formato WebP já ajuda)
- **Performance**: A página é leve e carrega rapidamente
- **Mobile**: Teste em dispositivos móveis para garantir boa experiência
- **Links**: Atualize os links de "Agendar Conversa" com seu formulário de contato real
