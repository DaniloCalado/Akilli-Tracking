# Akilli-Tracking

https://monitoramento-frontend-production.up.railway.app/

Entre com as credenciais de teste :
- login: Cliente_Teste
- senha: teste123

Plataforma de monotoramento de informações de clientes doque pesquisa informações do google e das redes sociais. o Banco de dados esta nosupabase.

-  É feito um crawler de uma pesquisa do cliente em toda a internet de forma diária.
-  Essas informações vão para o banco de dados
-  O Frontend possui a tela de login e partir do login do usuario ele vai buscar a tabela no banco de dados certa com as informações relacionada ao cliente.

Ao logar:
  - O Cliente visualiza as informações do mês atual com dominio descrição link para o site da noticia.
  - pode -se filtrar por tag ou por mês ( atualmente estamos colcoando só o ano atual)
  - Pode-se ver as informações em quadros do lado direito: 
    - Quantidade de noticoas negativas positivas e neutras.
    - Quantidade do tipo de noticia e da onde esta vindo as informoações e noticias
    - Top 5 maiores dominios da informação do mès.

Funcionalidades:
- Classificar a Notícia
- Remocar a noticia caso precise 
- Adicionar tags
- Remover tags
