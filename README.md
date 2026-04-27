Este programa registra em um pequeno banco de dados, uma lista com o nome dos professores, informações mínimas necessárias para se gerar o relatório de acordo com as normas locais, e gera um calendario em tabela automatizado com suas horas de HTPC, HSP e HE.

Ele permite editar os cadastros pra se adaptar a mudança de horário de professores, gerando lotes customizados com tudo ou parte dos dados registrados.

Todo mês após o cadastro, quando você precisa imprimir relatórios novos, você consegue gerar apenas informando o período que quer.

Você precisa ter as váriáveis do python instaladas no computador (pode fazer isso instalando por winget ou abrindo a store da microsoft)

Precisa dar pip install em três bibliotecas caso não as possua:
streamlit;
pandas;
python-docx;

Faça um arquivo de lotes (.bat) com essas três linhas:
pushd "Pasta onde está instalado o programa emefpedro"
python -m streamlit run emefpedro.py
pause

Talvez faça depois uma automatização na instalação e execução do mesmo, não acho que as pessoas vão utilizá-lo tanto assim, ta aí só por demonstração mesmo.

Bom trabalho amigos!
