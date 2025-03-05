### Perguntas
1. **Explique o conceito de ORM (Object-Relational Mapping) no Django.**
   - A) O ORM permite que você escreva consultas SQL diretamente no código.
   - B) O ORM é uma camada de abstração que mapeia tabelas do banco de dados para classes Python.
   - C) O ORM é usado apenas para relacionamentos muitos-para-muitos.
   - D) O ORM é uma ferramenta de segurança para proteger o banco de dados.

2. **Como você implementaria autenticação de usuário no Django?**
   - A) Usando apenas o módulo `django.contrib.auth`.
   - B) Criando um sistema personalizado sem o uso de `django.contrib.auth`.
   - C) Utilizando um serviço externo de autenticação.
   - D) Todas as alternativas acima.

3. **Qual é o propósito do arquivo `urls.py` em um projeto Django?**
   - A) Configurar o sistema de autenticação.
   - B) Definir as rotas da aplicação.
   - C) Configurar o banco de dados.
   - D) Gerenciar arquivos estáticos.

5. **Explique como você usaria middlewares no Django para adicionar funcionalidades às requisições e respostas.**
   - A) Middlewares são usados apenas para autenticação.
   - B) Middlewares são usados para filtrar requisições inválidas.
   - C) Middlewares podem adicionar dados às requisições ou respostas.
   - D) Middlewares são usados apenas para gerenciar sessões.

6. **Como você otimizaria o desempenho de um aplicativo Django que realiza muitas consultas ao banco de dados?**
   - A) Usando `select_related()` e `prefetch_related()` para reduzir o número de consultas.
   - B) Criando índices no banco de dados.
   - C) Utilizando uma ferramenta de cache para armazenar resultados frequentemente acessados.
   - D) Todas as alternativas acima.

7. **Qual é a diferença entre `select_related()` e `prefetch_related()` em Django?**
   - A) `select_related()` é usado para relacionamentos muitos-para-muitos, enquanto `prefetch_related()` é usado para relacionamentos um-para-muitos.
   - B) `select_related()` é usado para relacionamentos um-para-muitos, enquanto `prefetch_related()` é usado para relacionamentos muitos-para-muitos.
   - C) `select_related()` carrega dados em uma única consulta SQL, enquanto `prefetch_related()` carrega em consultas separadas.
   - D) `select_related()` é mais rápido que `prefetch_related()` em todos os casos.

8. **Como você lidaria com uma exceção em uma view Django para evitar que o servidor retorne um erro 500?**
   - A) Usando um bloco `try-except` para capturar a exceção e retornar uma resposta personalizada.
   - B) Ignorando a exceção e continuando a execução.
   - C) Redirecionando para uma página de erro genérica.
   - D) Usando um middleware para capturar todas as exceções.

10. **Explique o conceito de serialização no Django.**
    - A) Serialização é usada para converter dados em JSON.
    - B) Serialização é usada para converter dados em XML.
    - C) Serialização permite transformar dados do modelo em diversos formatos, como JSON ou XML.
    - D) Serialização é usada apenas para armazenar dados em cache.

11. **Como você diferenciaria projetos e aplicativos no Django?**
    - A) Projetos são maiores que aplicativos.
    - B) Aplicativos são componentes de um projeto.
    - C) Projetos são usados para organizar aplicativos.
    - D) Todas as alternativas acima.

12. **Qual é o propósito do arquivo `wsgi.py` em um projeto Django?**
    - A) Configurar o servidor de desenvolvimento.
    - B) Definir as rotas da aplicação.
    - C) Servir a aplicação Django em um servidor WSGI.
    - D) Executar comandos do Django.

13. **Explique como você usaria o comando `makemigrations` no Django.**
    - A) Para criar novas tabelas no banco de dados.
    - B) Para atualizar o esquema do banco de dados após alterações nos modelos.
    - C) Para excluir tabelas do banco de dados.
    - D) Para criar novos modelos.

14. **Como você configuraria arquivos estáticos no Django?**
    - A) Usando o arquivo `settings.py` para definir o caminho dos arquivos estáticos.
    - B) Usando o arquivo `urls.py` para servir os arquivos estáticos.
    - C) Usando um servidor de arquivos estáticos externo.
    - D) Todas as alternativas acima.

15. **Explique o conceito de sinais no Django.**
    - A) Sinais são usados para enviar e-mails.
    - B) Sinais são usados para realizar ações antes ou depois de eventos específicos no Django.
    - C) Sinais são usados apenas para autenticação.
    - D) Sinais são usados apenas para gerenciar sessões.
