# Typewriter Slides - Editor Visual + Apresentação

Uma ferramenta completa para criar apresentações minimalistas com efeito de máquina de escrever. Edição visual intuitiva e apresentação fullscreen com animação typewriter.

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Características Principais

### Editor Visual (WYSIWYG)
- **Edição inline** - Clique e edite diretamente nos slides
- **Slides verticais** - Todos visíveis e editáveis
- **Enter cria novo slide** automaticamente
- **Auto-delete** de slides vazios (0.8s)
- **Suporte a imagens** - Upload ou URL
- **Customização de cores** - Texto principal e cor de destaque
- **Auto-save** automático no localStorage
- **Numeração automática** dos slides

### Modo Apresentação Fullscreen
- **Efeito typewriter** letra por letra
- **Cursor piscando** animado
- **Slides progressivos** - Aparecem conforme você avança
- **Slides anteriores** ficam visíveis em cor mais clara
- **Imagens laterais** fixas durante apresentação
- **Slide atual** sempre centralizado
- **Controles rápidos** - Espaço pula animação, R reinicia
- **Botão Editar discreto** - Aparece só com movimento amplo do mouse

## Como Usar

### Início Rápido

1. **Abra `editor.html`** no seu navegador
2. **Edite os slides** clicando no texto (fica rosa)
3. **Pressione Enter** para criar novos slides
4. **Clique "Play"** para ver a apresentação
5. **Pressione E** ou mova o mouse para voltar ao editor

### Editando Slides

- **Clique no texto** → Entra em modo edição (texto rosa)
- **Digite normalmente** → Conteúdo é salvo automaticamente
- **Enter** → Cria novo slide abaixo
- **Apagar tudo** → Slide é deletado automaticamente (0.8s)
- **Backspace em vazio** → Deleta o slide também
- **Adicionar imagem** → Clique no botão em cada slide

### Navegação na Apresentação

| Tecla | Ação |
|-------|------|
| `→` ou `↓` | Avançar / Iniciar digitação |
| `←` ou `↑` | Voltar para slide anterior |
| `Espaço` | Iniciar ou pular animação typewriter |
| `R` | Reiniciar apresentação do início |
| `E` | Mostrar/esconder botão Editar |

### Personalizando Cores

1. Clique em **"Editar cores"** no toolbar
2. Escolha a **cor principal** (texto/highlight)
3. Escolha a **cor de destaque** (cursor, botões)
4. As cores são salvas automaticamente

## Funcionalidades Detalhadas

### Editor Visual

```
Recursos do Editor:
✓ Edição inline WYSIWYG
✓ Slides visíveis verticalmente
✓ Enter cria novo slide automaticamente
✓ Cursor vai direto para novo slide
✓ Slides vazios deletados automaticamente
✓ Numeração sequencial automática
✓ Upload ou URL de imagens
✓ Múltiplas imagens por slide
✓ Auto-save com indicador visual
✓ Personalização de cores
```

### Modo Apresentação

```
Recursos da Apresentação:
✓ Fullscreen centralizado
✓ Efeito typewriter letra por letra
✓ Cursor piscando durante digitação
✓ Slides anteriores visíveis (cor mais clara)
✓ Imagens fixas no lado direito
✓ Controle por teclado
✓ Reiniciar com tecla R
✓ Botão Editar ultra discreto
✓ Navegação bidirecional
```

## Estrutura do Projeto

```
typewriter-slides/
├── editor.html          # Editor visual + Apresentação (arquivo principal)
├── index.html           # Apresentação standalone (compatibilidade)
├── COMO-USAR.txt        # Manual detalhado em português
├── README.md            # Este arquivo
└── *.png               # Imagens de exemplo
```

## Tecnologias

- **HTML5** - Estrutura e contentEditable
- **CSS3** - Animações, transições, variáveis CSS
- **JavaScript Vanilla** - Sem frameworks ou dependências
- **localStorage** - Persistência de dados

## Armazenamento

O projeto salva automaticamente no **localStorage** do navegador:

```javascript
{
  slides: [...],        // Array de slides
  colors: {             // Cores personalizadas
    primary: "#142032",
    accent: "#f71963"
  },
  lastEdited: "..."     // Data da última edição
}
```

**Importante:**
- Dados salvos apenas no navegador atual
- Cada navegador tem seu próprio localStorage
- Dados persistem entre sessões

## Casos de Uso

- **Apresentações corporativas** minimalistas
- **Aulas e tutoriais** passo a passo
- **Slides para vídeos** com timing controlado
- **Portfolios interativos** com storytelling
- **Documentação técnica** apresentável
- **Apresentações criativas** com efeito retrô

## Diferenciais

- **Zero dependências** - Apenas HTML, CSS e JS
- **Offline-first** - Funciona sem internet
- **Leve e rápido** - ~60KB total
- **Fácil de usar** - Interface intuitiva
- **Totalmente customizável** - Cores, conteúdo, imagens
- **Open Source** - Código aberto e gratuito

## Responsividade

O projeto é **totalmente responsivo**:
- Desktop: Experiência completa
- Tablet: Ajustes de layout e fonte
- Mobile: Otimizado para tela pequena

## Privacidade

- **Dados locais** - Tudo fica no seu navegador
- **Sem tracking** - Zero analytics ou cookies
- **Sem servidor** - Não envia dados para nenhum lugar
- **100% offline** - Funciona sem conexão

## Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## Autor

Criado com cuidado usando HTML, CSS e JavaScript puro.

---

**Dica:** Para melhor experiência, use navegadores modernos (Chrome, Firefox, Safari, Edge).
