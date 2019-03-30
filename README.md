# Comandos Linux
- pwd	- mostrardiretório atual;
- ls 	- mostrar/listar o conteúdo do diretório;
- ps 	- Mostra os processos ativos de maneira detalhada;
- {comando} --help - informações sobre o comando (ajuda);
- top 	- Monitora continuamente os processos, mostrando informações como uso de memória e CPU de cada processo;
- CTRL + C - Cancela a execução de qualquer comando executado;
- chmod + {
	+ adicionar permisão
	- remover permisão
	= igualar permisão
	}
Exemplo do uso do "chmod": chmod +x arq.txt
# Tipos de permissões de acesso
- r - Ler 
- w - gravar
- x - executar para arquivos e acessar diretório
# Tipos de permissões no modo octal

- 7 -> todas permissões
- 6 -> ler + gravar
- 5 -> ler + executar
- 4 -> ler(r)
- 3 -> gravar e executar
- 2 -> gravar(w)
- 1 -> executar(x)
- 0 -> Nenhuma permissão
exemplo
- chmod 664 arq.txt
- usuários (dono)
- grupo
- outros
