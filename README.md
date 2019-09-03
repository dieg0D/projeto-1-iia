## Universidade de Brasília
## Departamento de Ciência da Computação
## Introdução à Inteligência Artificial, Turma A, 2/2019
## Projeto 1
## Prof. Díbio
## Alunos: Diego Antonio Barbosa cardoso - 16/0005116 , Matheus Rodrigues Guimaraes - 15/0141661

### Para rodar o dfs utilize:
    python3 pacman.py -l mediumMaze -p SearchAgent -a fn=depthFirstSearch

### Para rodar o a* com  a primeira heuristica utilize:
    python3 pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=diagonalHeuristic

### Para rodar o a* com  a segunda heuristica utilize:
    python3 pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=produtoCruzado
