# Política de Segurança / Security Policy

## 🔒 Compromisso com Segurança / Security Commitment

### 🇧🇷 Português

A segurança do projeto DRBIII_Arduino_Speeduino e de seus usuários é uma prioridade máxima. Este documento estabelece nossas políticas de segurança e como reportar vulnerabilidades de forma responsável.

**IMPORTANTE**: Este projeto envolve sistemas automotivos críticos. Vulnerabilidades de segurança podem afetar a segurança do veículo e seus ocupantes.

### 🇺🇸 English

The security of the DRBIII_Arduino_Speeduino project and its users is a top priority. This document establishes our security policies and how to responsibly report vulnerabilities.

**IMPORTANT**: This project involves critical automotive systems. Security vulnerabilities can affect vehicle safety and its occupants.

---

## 🛡️ Versões Suportadas / Supported Versions

### 🇧🇷 Português

Atualmente, damos suporte de segurança para as seguintes versões:

### 🇺🇸 English

We currently provide security support for the following versions:

| Versão / Version | Suportada / Supported | Notas / Notes |
| ------- | ------------------ | ----- |
| main (development) | ✅ | Versão em desenvolvimento / Development version |
| 1.0.x (quando lançada) | ✅ | Primeira versão estável / First stable version |
| < 1.0 | ⚠️ | Pré-lançamento / Pre-release |

---

## 🚨 Reportando Vulnerabilidades / Reporting Vulnerabilities

### 🇧🇷 Português

**Por favor, NÃO reporte vulnerabilidades de segurança através de issues públicas do GitHub.**

#### Como Reportar de Forma Segura:

1. **Contato Privado**:
   - Envie um e-mail para o mantenedor: @iurygoncalves (via GitHub ou e-mail privado)
   - Use a opção "Security Advisory" do GitHub (se disponível)
   - Entre em contato via mensagem direta

2. **Informações a Incluir**:
   - Descrição detalhada da vulnerabilidade
   - Passos para reproduzir o problema
   - Impacto potencial (criticidade)
   - Versão afetada do software
   - Possível solução ou mitigação (se conhecida)
   - Seu nome/contato para crédito (opcional)

3. **O Que Esperar**:
   - **Confirmação em 48 horas**: Confirmaremos o recebimento
   - **Avaliação em 7 dias**: Avaliaremos a severidade
   - **Correção em 30 dias**: Para vulnerabilidades críticas
   - **Crédito Público**: Com sua permissão, você será creditado

#### Exemplo de Reporte:

```
Assunto: [SEGURANÇA] Vulnerabilidade no módulo SCI_Communication

Descrição: Descobri uma vulnerabilidade que permite...

Impacto: Alta - Pode causar...

Passos para Reproduzir:
1. ...
2. ...
3. ...

Versão Afetada: main branch, commit abc123

Possível Solução: ...

Contato: [seu nome/email]
```

### 🇺🇸 English

**Please DO NOT report security vulnerabilities through public GitHub issues.**

#### How to Report Safely:

1. **Private Contact**:
   - Email the maintainer: @iurygoncalves (via GitHub or private email)
   - Use GitHub's "Security Advisory" option (if available)
   - Contact via direct message

2. **Information to Include**:
   - Detailed vulnerability description
   - Steps to reproduce the issue
   - Potential impact (criticality)
   - Affected software version
   - Possible solution or mitigation (if known)
   - Your name/contact for credit (optional)

3. **What to Expect**:
   - **Confirmation within 48 hours**: We'll confirm receipt
   - **Assessment within 7 days**: We'll assess severity
   - **Fix within 30 days**: For critical vulnerabilities
   - **Public Credit**: With your permission, you'll be credited

#### Report Example:

```
Subject: [SECURITY] Vulnerability in SCI_Communication module

Description: I discovered a vulnerability that allows...

Impact: High - Can cause...

Steps to Reproduce:
1. ...
2. ...
3. ...

Affected Version: main branch, commit abc123

Possible Solution: ...

Contact: [your name/email]
```

---

## 🎯 Categorias de Vulnerabilidades / Vulnerability Categories

### 🇧🇷 Português / 🇺🇸 English

#### 🔴 Crítica / Critical
- Comprometimento da segurança do veículo / Vehicle safety compromise
- Acesso não autorizado à ECU / Unauthorized ECU access
- Falhas que podem causar acidentes / Failures that could cause accidents
- **Tempo de resposta / Response time**: 24-48 horas / hours

#### 🟠 Alta / High
- Perda de dados de calibração / Calibration data loss
- Falhas de comunicação críticas / Critical communication failures
- Vulnerabilidades de injeção de código / Code injection vulnerabilities
- **Tempo de resposta / Response time**: 7 dias / days

#### 🟡 Média / Medium
- Problemas de performance / Performance issues
- Vazamento de informações não críticas / Non-critical information leaks
- Bugs que afetam funcionalidades / Bugs affecting functionality
- **Tempo de resposta / Response time**: 14 dias / days

#### 🟢 Baixa / Low
- Problemas cosméticos / Cosmetic issues
- Melhorias de código / Code improvements
- Documentação / Documentation
- **Tempo de resposta / Response time**: 30 dias / days

---

## 🔐 Práticas de Segurança / Security Practices

### 🇧🇷 Para Desenvolvedores / 🇺🇸 For Developers

#### ✅ Faça / Do:
- Valide todas as entradas / Validate all inputs
- Use comunicação criptografada quando possível / Use encrypted communication when possible
- Teste extensivamente em ambiente seguro / Test extensively in safe environment
- Documente mudanças de segurança / Document security changes
- Revise código antes de commits / Review code before commits
- Use constantes para valores críticos / Use constants for critical values

#### ❌ Não Faça / Don't:
- Commitar credenciais ou chaves / Commit credentials or keys
- Ignorar avisos do compilador / Ignore compiler warnings
- Desabilitar verificações de segurança / Disable security checks
- Usar funções depreciadas / Use deprecated functions
- Testar em veículos em movimento / Test in moving vehicles
- Modificar valores críticos sem validação / Modify critical values without validation

### 🇧🇷 Para Usuários / 🇺🇸 For Users

#### ✅ Faça / Do:
- Faça backup antes de atualizar / Backup before updating
- Teste em bancada primeiro / Test on bench first
- Use versões estáveis / Use stable versions
- Reporte comportamentos estranhos / Report strange behaviors
- Siga documentação oficial / Follow official documentation
- Mantenha software atualizado / Keep software updated

#### ❌ Não Faça / Don't:
- Use em produção sem testes / Use in production without testing
- Modifique parâmetros críticos aleatoriamente / Randomly modify critical parameters
- Ignore avisos de segurança / Ignore security warnings
- Compartilhe configurações não testadas / Share untested configurations
- Desabilite proteções / Disable protections

---

## 🚗 Segurança Automotiva / Automotive Safety

### ⚠️ Avisos Importantes / Important Warnings

#### 🇧🇷 Português

Este software interage com sistemas críticos do veículo:

1. **Testes**: Sempre teste em bancada antes de instalar no veículo
2. **Calibração**: Use valores de calibração seguros e validados
3. **Monitoramento**: Monitore parâmetros críticos durante uso
4. **Reversão**: Tenha sempre capacidade de reverter para configuração original
5. **Suporte**: Em caso de problemas, desabilite imediatamente

**NUNCA**:
- Teste funcionalidades desconhecidas em trânsito
- Modifique parâmetros de segurança sem compreensão total
- Use versões não testadas em veículos de uso diário
- Ignore comportamentos anormais do motor

#### 🇺🇸 English

This software interacts with critical vehicle systems:

1. **Testing**: Always test on bench before installing in vehicle
2. **Calibration**: Use safe and validated calibration values
3. **Monitoring**: Monitor critical parameters during use
4. **Rollback**: Always have capability to revert to original configuration
5. **Support**: In case of problems, disable immediately

**NEVER**:
- Test unknown features while driving
- Modify safety parameters without full understanding
- Use untested versions in daily use vehicles
- Ignore abnormal engine behaviors

---

## 📋 Checklist de Segurança / Security Checklist

### Antes de Contribuir / Before Contributing

- [ ] Código foi testado em ambiente seguro / Code tested in safe environment
- [ ] Não contém credenciais ou dados sensíveis / No credentials or sensitive data
- [ ] Validações de entrada implementadas / Input validations implemented
- [ ] Documentação de segurança atualizada / Security documentation updated
- [ ] Revisão de código realizada / Code review performed
- [ ] Testes de regressão passaram / Regression tests passed

### Antes de Usar / Before Using

- [ ] Backup da configuração original / Backup of original configuration
- [ ] Compreensão da funcionalidade / Understanding of functionality
- [ ] Ambiente de teste disponível / Test environment available
- [ ] Plano de reversão preparado / Rollback plan prepared
- [ ] Monitoramento configurado / Monitoring configured
- [ ] Documentação lida e compreendida / Documentation read and understood

---

## 🏅 Programa de Reconhecimento / Recognition Program

### 🇧🇷 Português

Valorizamos pesquisadores de segurança responsáveis:

1. **Hall da Fama de Segurança**: Seu nome será listado (com permissão)
2. **Crédito Público**: Reconhecimento na release note da correção
3. **Referência**: Podemos fornecer referência para seu trabalho
4. **Colaboração**: Oportunidade de colaborar na correção

### 🇺🇸 English

We value responsible security researchers:

1. **Security Hall of Fame**: Your name will be listed (with permission)
2. **Public Credit**: Recognition in the fix release note
3. **Reference**: We can provide reference for your work
4. **Collaboration**: Opportunity to collaborate on the fix

---

## 📊 Histórico de Segurança / Security History

### Vulnerabilidades Reportadas / Reported Vulnerabilities

_Nenhuma vulnerabilidade reportada até o momento._

_No vulnerabilities reported so far._

Formato de divulgação:
- **ID**: CVE-YYYY-XXXXX (se aplicável)
- **Data**: DD/MM/YYYY
- **Severidade**: Crítica/Alta/Média/Baixa
- **Descrição**: Breve descrição
- **Correção**: Versão da correção
- **Crédito**: Pesquisador (se autorizado)

---

## 📞 Contatos de Emergência / Emergency Contacts

### Para Vulnerabilidades Críticas / For Critical Vulnerabilities

- **Mantenedor Principal**: @iurygoncalves
- **GitHub Security**: Use GitHub Security Advisory
- **Resposta Esperada**: 24 horas para vulnerabilidades críticas

---

## 📚 Recursos Adicionais / Additional Resources

- [OWASP Embedded Application Security](https://owasp.org/www-project-embedded-application-security/)
- [Automotive Cybersecurity Best Practices](https://www.nhtsa.gov/document/cybersecurity-best-practices-modern-vehicles)
- [Arduino Security Guidelines](https://www.arduino.cc/en/security)

---

**Versão / Version**: 1.0  
**Última Atualização / Last Update**: Dezembro/December 2025

**A segurança é responsabilidade de todos. Obrigado por nos ajudar a manter o projeto seguro!**

**Security is everyone's responsibility. Thank you for helping us keep the project safe!**
