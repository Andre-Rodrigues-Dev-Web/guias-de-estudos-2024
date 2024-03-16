# Mapa Mental de Estudos para Angular

## 1. Introdução ao Angular
   - Visão geral do Angular
   - História e evolução
   - Arquitetura e conceitos básicos
     - Componentes
     - Módulos
     - Diretivas
     - Serviços
     - Injeção de dependência

## 2. Configuração do Ambiente
   - Instalação do Node.js e npm
   - Instalação do Angular CLI
   - Configuração do ambiente de desenvolvimento
     - Configuração do TypeScript
     - Configuração do IDE (por exemplo, Visual Studio Code)

## 3. Componentes
   - Criando e utilizando componentes
     - Estrutura de arquivos de componente
     - Ciclo de vida dos componentes
   - Comunicação entre componentes
     - @Input e @Output
     - Serviços
     - RxJS para comunicação entre componentes

## 4. Templates e Diretivas
   - Utilizando templates
     - Interpolação
     - Diretivas estruturais (*ngIf, *ngFor)
   - Diretivas de atributo
     - Event binding
     - Property binding
     - Two-way data binding

## 5. Módulos e Injeção de Dependência
   - Organização em módulos
     - Módulos raiz
     - Módulos de funcionalidades
   - Injeção de dependência no Angular
     - Hierarquia de injetores
     - Injetando serviços

## 6. Roteamento
   - Configuração de rotas
     - RouterModule.forRoot()
     - Rotas filhas
   - Roteamento com parâmetros
     - Parâmetros de rota
     - Parâmetros de consulta
   - Roteamento aninhado e lazy loading
     - Lazy loading de módulos
     - Lazy loading de componentes

## 7. Formulários
   - Formulários template-driven
     - Validação de entrada de dados
     - Custom validators
   - Formulários reativos
     - FormGroup e FormControl
     - Validação assíncrona
   - Validação de formulários
     - Validação de campo
     - Validação de formulário completo

## 8. Serviços e HTTP
   - Criação e utilização de serviços
     - Singleton services
     - Services com estado
   - Integração com serviços HTTP
     - HttpClientModule
     - CRUD operations
   - Interceptor HTTP e manipulação de erros
     - Adicionando cabeçalhos HTTP
     - Interceptando erros HTTP

## 9. RxJS no Angular
   - Observables e subscrições
     - Observables vs Promises
     - Subscription management
   - Utilização de operadores
     - Map, Filter, MergeMap, SwitchMap, etc.
   - Gerenciamento de fluxos de dados assíncronos
     - Avoiding memory leaks
     - Cancellation and completion strategies

## 10. Testes
    - Testes unitários
      - TestBed e mocks
      - Testando componentes, serviços e pipes
    - Testes de integração
      - Testando módulos e componentes integrados
    - Utilizando ferramentas de teste no Angular
      - Jasmine e Karma
      - Protractor para testes end-to-end

## 11. Desempenho e Otimização
    - Estratégias de otimização de desempenho
      - AOT (Ahead-of-Time compilation)
      - Minificação e tree shaking
    - Lazy loading de módulos e componentes
      - Otimizando o carregamento de recursos
    - Detecção de mudanças e otimização de detecção
      - Change detection strategies
      - OnPush change detection

## 12. Segurança
    - Práticas recomendadas de segurança no Angular
      - Cross-site scripting (XSS)
      - Cross-site request forgery (CSRF)
    - Proteção contra ataques comuns
      - Sanitização de entrada de dados
      - Autenticação e autorização
    - Utilização de bibliotecas de segurança
      - Angular Security Library
      - OWASP Angular Security Checklist
