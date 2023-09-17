# nlw-ai-mastery
Gerador de títulos e descrições para vídeos com a utilização de inteligência artificial.
<br>A aplicação foi desenvolvida com base nas aulas do evento gratuito NLW IA Trilha Mastery da RocketSeat, apresentado pelo Co-founder & CTO Diego Fernandes. 

# Aplicação
Para rodar a aplicação use o comando ```npm run dev``` no projeto web e no projeto server. Ambos os projetos devem estar em execução para o funcionamento da aplicação.

# Server
Para o funcionamento da aplicação é necessário ter o arquivo .env dentro do projeto server. O arquivo deve conter as seguintes linhas de comando:
<br>------------<br> #Database <br> DATABASE_URL="file:./dev.db" <br><br> #OPENAI <br> OPENAI_KEY=" " <br>
<br>------------<br> Para obter a "openai key" é necessário que o usuário tenha uma conta no site da OpenAI e crie uma secret key (pode ser criada em "ver chaves API" no perfil do usuário).
