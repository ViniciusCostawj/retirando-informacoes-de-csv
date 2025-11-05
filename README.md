Este script automatiza a separação de dados de um arquivo CSV com base em uma coluna específica. Ele identifica os registros que possuem “BOOK” e “INFO” na coluna “StatusCode” e os salva em arquivos separados. É útil para análises segmentadas, controle de logs e pré-processamento de dados.

⚙️ Funcionalidades

Verifica se o arquivo original existe.

Lê o CSV e identifica a coluna-alvo (StatusCode).

Cria dois arquivos de saída:

saida_book.csv → registros com “BOOK”.

saida_info.csv → registros com “INFO”.

Exibe logs informativos e mensagens de erro claras.

📂 Arquivos Gerados
Arquivo	Descrição
saida_book.csv	Contém as linhas em que StatusCode = “BOOK”.
saida_info.csv	Contém as linhas em que StatusCode = “INFO”.
🚀 Como Executar

Certifique-se de que o arquivo TODOS_os_dados_filtrados.csv.csv está no mesmo diretório do script.

No terminal, execute:

python separador_csv.py


Os arquivos saida_book.csv e saida_info.csv serão gerados automaticamente.

🧩 Dependências

Python 3.x

pandas

Instale as dependências com:

pip install pandas

🧑‍💻 Autor

Desenvolvido por Vinicius Costa de Paula, profissional de TI especializado em automação de processos, análise de dados e desenvolvimento em Python.
