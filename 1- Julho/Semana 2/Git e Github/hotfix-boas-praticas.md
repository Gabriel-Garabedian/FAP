# 📚 - Hotfix e Boas Práticas

## 🎯 Objetivo

Aprender práticas utilizadas em ambientes profissionais.

---

## 🧠 Tipos de Branch

### Feature

Nova funcionalidade.

```text
feature-login
```

### Bugfix

Correção comum.

```text
bugfix-validacao-cpf
```

### Hotfix

Correção urgente em produção.

```text
hotfix-login-producao
```

---

## 🚨 Quando usar Hotfix?

Quando existe um problema crítico em produção.

Exemplo:

```text
Usuários não conseguem fazer login.
Sistema fora do ar.
```

---

## 💻 Boas Mensagens de Commit

✅ Bom:

```bash
git commit -m "Corrige erro de autenticação"
```

✅ Bom:

```bash
git commit -m "Adiciona recuperação de senha"
```

❌ Ruim:

```bash
git commit -m "mudancas"
```

---

## 🏢 Fluxo de Hotfix

```text
Problema em Produção
↓
Criar Hotfix
↓
Corrigir
↓
Testar
↓
Push
↓
Pull Request
↓
Merge
↓
Voltar para a Feature
```

---

## 📝 Resumo

- Use nomes descritivos.
- Use commits claros.
- Hotfix serve para correções urgentes.
- Não misture correções urgentes com features inacabadas.