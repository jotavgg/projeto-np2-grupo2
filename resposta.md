navigate_tree:

É uma função de estrutura de decisão com base em valores binários (sim/não) que valida as respostas e percorre a árvore de escolhas do app_tree.py

connected: 

é uma função de validação que detecta o input do usuário, converte para a norma (return x.strip().lower() if isinstance(x, str) else x) e compara os inputs a e b com um dicionário em app_graph.py pela relação chave -> valor ou valor -> chave, ex: "Ana" = ["Bruno", ...], se a relação existe, retorna uma mensagem de confirmação "... estão conectados" se não, "... Não estão conectados"