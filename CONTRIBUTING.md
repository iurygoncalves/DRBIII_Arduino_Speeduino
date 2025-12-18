# Guia de Contribuição / Contributing Guide

## 🇧🇷 Português

### Bem-vindo(a)!

Obrigado por considerar contribuir para o projeto DRBIII_Arduino_Speeduino! Este documento estabelece diretrizes claras para proteger seus direitos como colaborador(a) e garantir um processo transparente e justo.

### 📜 Seus Direitos Como Contribuidor(a)

#### 1. Propriedade Intelectual
- Você mantém os direitos autorais sobre suas contribuições originais
- Ao contribuir, você concede uma licença MIT para o projeto
- Você pode reutilizar suas próprias contribuições em outros projetos

#### 2. Atribuição e Reconhecimento
- Todas as contribuições são registradas no histórico Git
- Contribuidores significativos são listados em CONTRIBUTORS.md
- Seu nome e contribuição serão sempre preservados

#### 3. Proteção Legal
- Você não é responsável por problemas decorrentes do uso do software
- A responsabilidade pelo projeto é do mantenedor principal
- Licença MIT protege contribuidores de responsabilidade civil

#### 4. Liberdade de Participação
- Você pode contribuir quando e como desejar
- Não há obrigações contínuas após uma contribuição
- Você pode parar de contribuir a qualquer momento

#### 5. Ambiente Respeitoso
- Conduta profissional é exigida de todos
- Consulte CODE_OF_CONDUCT.md para padrões da comunidade
- Assédio e discriminação não serão tolerados

### 🔧 Como Contribuir

#### Passo 1: Fork do Repositório
```bash
# Clone seu fork
git clone https://github.com/seu-usuario/DRBIII_Arduino_Speeduino.git
cd DRBIII_Arduino_Speeduino

# Adicione o repositório original como upstream
git remote add upstream https://github.com/iurygoncalves/DRBIII_Arduino_Speeduino.git
```

#### Passo 2: Crie uma Branch
```bash
# Crie uma branch descritiva para sua feature ou correção
git checkout -b feature/minha-nova-funcionalidade
# ou
git checkout -b fix/correcao-de-bug
```

#### Passo 3: Faça suas Alterações
- Escreva código claro e bem documentado
- Siga o estilo de código existente
- Teste suas alterações localmente
- Adicione comentários quando necessário

#### Passo 4: Commit das Alterações
```bash
# Adicione os arquivos modificados
git add .

# Faça commit com mensagem descritiva
git commit -m "feat: adiciona suporte para novo sensor"
# ou
git commit -m "fix: corrige leitura do barramento CCD"
```

**Convenções de Commit:**
- `feat:` - Nova funcionalidade
- `fix:` - Correção de bug
- `docs:` - Apenas documentação
- `style:` - Formatação de código
- `refactor:` - Refatoração de código
- `test:` - Adição de testes
- `chore:` - Manutenção geral

#### Passo 5: Push e Pull Request
```bash
# Envie para seu fork
git push origin feature/minha-nova-funcionalidade
```

Então, no GitHub:
1. Vá até seu fork do repositório
2. Clique em "Pull Request"
3. Preencha o template com detalhes sobre sua contribuição
4. Aguarde revisão do mantenedor

### 📋 Checklist de Pull Request

Antes de submeter, certifique-se:
- [ ] O código compila sem erros
- [ ] Funcionalidade foi testada
- [ ] Documentação foi atualizada (se necessário)
- [ ] Commits seguem as convenções
- [ ] Código segue o estilo do projeto

### 🐛 Reportando Bugs

Para reportar um bug:
1. Verifique se já não foi reportado
2. Use o template de issue para bugs
3. Inclua:
   - Descrição clara do problema
   - Passos para reproduzir
   - Comportamento esperado vs. atual
   - Ambiente (versão Arduino, placa, etc.)
   - Logs ou mensagens de erro

### 💡 Sugerindo Melhorias

Para sugerir uma nova funcionalidade:
1. Verifique se já não foi sugerida
2. Use o template de issue para features
3. Explique:
   - O problema que resolve
   - Como funcionaria
   - Benefícios para o projeto

### 🤝 Acordo de Contribuição

Ao contribuir para este projeto, você concorda que:

1. **Licenciamento**: Suas contribuições serão licenciadas sob MIT License
2. **Originalidade**: Seu código é original ou você tem direito de contribuí-lo
3. **Conduta**: Você seguirá o Code of Conduct do projeto
4. **Responsabilidade**: O mantenedor do projeto assume responsabilidade pelas decisões de integração

### 🔒 Segurança

- Não inclua informações sensíveis no código
- Para vulnerabilidades de segurança, veja SECURITY.md
- Use comunicação privada para questões críticas de segurança

### 📞 Dúvidas?

- Abra uma issue com a tag `question`
- Entre em contato com @iurygoncalves
- Consulte a documentação em `/docs`

---

## 🇺🇸 English

### Welcome!

Thank you for considering contributing to DRBIII_Arduino_Speeduino! This document establishes clear guidelines to protect your rights as a contributor and ensure a transparent and fair process.

### 📜 Your Rights as a Contributor

#### 1. Intellectual Property
- You retain copyright over your original contributions
- By contributing, you grant an MIT license to the project
- You may reuse your own contributions in other projects

#### 2. Attribution and Recognition
- All contributions are recorded in Git history
- Significant contributors are listed in CONTRIBUTORS.md
- Your name and contribution will always be preserved

#### 3. Legal Protection
- You are not liable for issues arising from software use
- Project responsibility lies with the main maintainer
- MIT License protects contributors from civil liability

#### 4. Freedom of Participation
- You can contribute when and how you wish
- No ongoing obligations after a contribution
- You may stop contributing at any time

#### 5. Respectful Environment
- Professional conduct is required from everyone
- See CODE_OF_CONDUCT.md for community standards
- Harassment and discrimination will not be tolerated

### 🔧 How to Contribute

#### Step 1: Fork the Repository
```bash
# Clone your fork
git clone https://github.com/your-username/DRBIII_Arduino_Speeduino.git
cd DRBIII_Arduino_Speeduino

# Add original repository as upstream
git remote add upstream https://github.com/iurygoncalves/DRBIII_Arduino_Speeduino.git
```

#### Step 2: Create a Branch
```bash
# Create a descriptive branch for your feature or fix
git checkout -b feature/my-new-feature
# or
git checkout -b fix/bug-fix
```

#### Step 3: Make Your Changes
- Write clear and well-documented code
- Follow existing code style
- Test your changes locally
- Add comments when necessary

#### Step 4: Commit Changes
```bash
# Add modified files
git add .

# Commit with descriptive message
git commit -m "feat: add support for new sensor"
# or
git commit -m "fix: correct CCD bus reading"
```

**Commit Conventions:**
- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation only
- `style:` - Code formatting
- `refactor:` - Code refactoring
- `test:` - Adding tests
- `chore:` - General maintenance

#### Step 5: Push and Pull Request
```bash
# Push to your fork
git push origin feature/my-new-feature
```

Then, on GitHub:
1. Go to your repository fork
2. Click "Pull Request"
3. Fill template with details about your contribution
4. Wait for maintainer review

### 📋 Pull Request Checklist

Before submitting, ensure:
- [ ] Code compiles without errors
- [ ] Functionality has been tested
- [ ] Documentation updated (if necessary)
- [ ] Commits follow conventions
- [ ] Code follows project style

### 🐛 Reporting Bugs

To report a bug:
1. Check if it hasn't been reported already
2. Use the bug issue template
3. Include:
   - Clear problem description
   - Steps to reproduce
   - Expected vs. actual behavior
   - Environment (Arduino version, board, etc.)
   - Logs or error messages

### 💡 Suggesting Improvements

To suggest a new feature:
1. Check if it hasn't been suggested already
2. Use the feature issue template
3. Explain:
   - The problem it solves
   - How it would work
   - Benefits for the project

### 🤝 Contribution Agreement

By contributing to this project, you agree that:

1. **Licensing**: Your contributions will be licensed under MIT License
2. **Originality**: Your code is original or you have rights to contribute it
3. **Conduct**: You will follow the project's Code of Conduct
4. **Responsibility**: The project maintainer assumes responsibility for integration decisions

### 🔒 Security

- Do not include sensitive information in code
- For security vulnerabilities, see SECURITY.md
- Use private communication for critical security issues

### 📞 Questions?

- Open an issue with the `question` tag
- Contact @iurygoncalves
- Check documentation in `/docs`

---

**Obrigado por contribuir! / Thank you for contributing!** 🚀
