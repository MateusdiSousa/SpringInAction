# Resumo: Spring in Action 4ª Edição - Capítulos Iniciais

## Introdução ao Spring
- **Objetivo principal**: Reduzir a complexidade de aplicações empresariais Java.
- **Princípios fundamentais**:
  - Simplicidade
  - Testabilidade
  - Desacoplamento (através de Beans e Injeção de Dependência)

## O que são Beans?
- **Definição**: Componentes gerenciados pelo Spring.
- **Característica**: Qualquer POJO (Plain Old Java Object) pode ser um Bean.

## Como o Spring reduz complexidade?
1. **Desenvolvimento leve**:
   - Minimamente invasivo com POJOs
2. **Desacoplamento**:
   - Injeção de Dependência
   - Orientação a interfaces
3. **Programação declarativa**:
   - Uso de aspectos e convenções comuns
4. **Redução de código repetitivo**:
   - Através de aspectos e templates

## Injeção de Dependência
[🔗 Link para notas detalhadas]

### Funcionamento:
- **Problema resolvido**: Alto acoplamento entre classes.
- **Solução**: 
  - Ao invés da classe criar seus próprios objetos de dependência
  - Ela recebe esses objetos prontos (via construtor ou métodos)

## AOP (Programação Orientada a Aspectos)
[🔗 Link para notas detalhadas]

### Conceito:
- Paradigma complementar ao OOP
- Modulariza "cross-cutting concerns" (preocupações transversais)

### Casos de uso comuns:
- ✅ Logging
- ✅ Segurança (Security)
- ✅ Transações (Transactions)
- ✅ Monitoramento (Performance Tracking)
- ✅ Tratamento de Exceções Centralizado

### Vantagem:
- Resolve o problema de repetição de código (ex: lógica de log em múltiplas classes)
- Separa essas preocupações em **aspectos** (módulos independentes)
- Aplica dinamicamente ao código quando necessário
