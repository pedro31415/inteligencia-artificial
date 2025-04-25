# Resumo de Inteligência Artificial

## 🤖 O que seria Inteligência Artificial?

A **Inteligência Artificial (IA)** é o campo da ciência da computação que busca desenvolver sistemas ou máquinas capazes de **simular comportamentos inteligentes**, como **aprender**, **raciocinar**, **resolver problemas**, **perceber** o ambiente e até mesmo se comunicar em linguagem natural.

A IA pode ser dividida em diferentes abordagens de estudo:

---

## 📌 Questões Éticas:

1. Preconceitos e Discriminação em Algoritmos
2. Privacidade e Segurança de Dados
3. Autonomia e Controle
4. Impacto no Mercado de Trabalho
5. Transparência e Explicabilidade
6. Responsabilidade e Accountability
7. Manipulação e Fake News
8. Ética no Desenvolvimento de IA
9. Impactos Ambientais
10. Riscos de Superinteligência e Controle Global

---

## 📌 Categorias da IA:

### 1. **Sistemas que pensam como humanos**
- Objetivo: simular o processo de **pensamento humano**.
- Exemplo: Modelos cognitivos, como redes neurais que tentam replicar o funcionamento do cérebro.

### 2. **Sistemas que agem como humanos**
- Objetivo: **agir como uma pessoa**, imitando seu comportamento.
- Exemplo: Robôs humanoides, assistentes virtuais (como o Siri), e o próprio ChatGPT.

### 3. **Sistemas que pensam racionalmente**
- Objetivo: **pensar de maneira lógica**, baseada em regras e inferências.
- Exemplo: Sistemas especialistas baseados em lógica formal.

### 4. **Sistemas que agem racionalmente**
- Objetivo: **agir da melhor forma possível** para alcançar um objetivo.
- Exemplo: Carros autônomos, agentes inteligentes que tomam decisões com base em situações.

> 💬 O ChatGPT se encaixa principalmente como **sistema que age como humano** (processamento de linguagem natural), mas também pode ser visto como **sistema que pensa racionalmente**.

---

## 🧬 Linhas de Pesquisa em IA:

### 🔹 Simbólica (ou simbólica clássica)
- Representa conhecimento com **símbolos e regras lógicas**.
- Exemplo: Sistemas especialistas, Prolog.

### 🔹 Conexionista
- Inspira-se na **estrutura do cérebro humano** (redes neurais).
- Exemplo: Machine Learning e Deep Learning.

### 🔹 Evolucionária
- Baseada em mecanismos de **evolução natural**.
- Exemplo: Algoritmos Genéticos e Programação Evolutiva.

---

## 📖 Breve Histórico

### 🧐 Quando surgiu o termo IA?
-  A primeira manifestação oficial de IA foi registrada em 1956 na
Conferência de Darthmouth.

### 💻 Pesquisadores que contribuíram para a criação do campo da IA:
-  John McCarthy: cunhou o termo inteligência artificial.
-  Marvin Minsky: Construiu o primeiro computador com base em redes
neurais. Descreveu a incapacidade do perceptron simples resolver problemas
como o XOR.
-  Nathaniel ROchester: Simulou o comportamento de redes neurais abstratas
em um computador IBM 704.
-  Norbert Wiener: Fundador da cibernética. Desenvolveu estudos de sistemas
autorregulados e formulou o conceito de retroalimentação negativa.
- Frank Rosenblatt: Inventou o perpectron.

---

## 🧠 Agente, Função do Agente e Agente Inteligente

- **Agente**: entidade que percebe o ambiente e age sobre ele.
- **Função do agente**: mapeia percepções para ações.
- **Agente Inteligente**: escolhe ações que **maximizam seu desempenho** com base nas percepções e conhecimento.

---

## 🎯 Quatro fatores que definem a racionalidade de um agente:

1. **Medição de desempenho**: critério para avaliar o sucesso da tarefa.
2. **Conhecimento prévio**: o que o agente já sabe sobre o ambiente.
3. **Ações possíveis**: conjunto de ações que o agente pode realizar.
4. **Sequência de percepções**: histórico de tudo o que foi percebido até o momento.

---

## 🌍 Propriedades do ambiente de tarefas:

- **Observável**: o agente tem acesso total (ou não) ao estado do ambiente.
- **Determinístico**: o próximo estado depende apenas do estado atual e ação do agente.
- **Episódico**: decisões independentes (ou dependentes) de episódios anteriores.
- **Estático**: o ambiente muda apenas com as ações do agente.
- **Discreto**: número finito de ações/percepções.
- **Agente**: o sistema que atua no ambiente.

---

## ⚙️ Tipos de Estrutura de Agentes

### 1. Agentes Reativos Simples
- Baseados em regras simples “Se-então”.
- **Exemplo**: sensor de luz, robô aspirador básico.

### 2. Agentes Reativos Baseados em Modelo
- Têm memória/estado interno.
- **Exemplo**: carro autônomo que lembra obstáculos.

### 3. Agentes Baseados em Objetivos
- Tomam decisões com base em objetivos a alcançar.
- **Exemplo**: robô de entrega que escolhe a melhor rota.

### 4. Agentes Baseados na Utilidade
- Avaliam qual ação traz maior “satisfação” ou benefício.
- **Exemplo**: carro autônomo que busca o caminho mais seguro e rápido.

---

## 📚 Agente de Aprendizagem e seus Elementos Conceituais

Um **agente de aprendizagem** melhora com o tempo, aprendendo a partir da experiência. Ele é composto por:

### • Elemento de Desempenho:
Executa ações com base no conhecimento atual.

### • Elemento Crítico:
Avalia o desempenho e identifica o que precisa melhorar.

### • Elemento de Aprendizado:
Atualiza o agente com base na avaliação do elemento crítico.

### • Gerador de Problemas:
Cria novas situações para o agente explorar e aprender.

---

## 🧩 Resolução de Problemas por Busca — 4 Componentes

### 🔹 1. Estado Inicial
> Situação de partida do problema. Define onde o agente começa.

**Exemplo**: No jogo de xadrez, é a posição inicial das peças.

### 🔹 2. Função Sucessor
> Conjunto de ações possíveis e os estados resultantes.

**Exemplo**: Em um jogo, quais movimentos são possíveis a partir do estado atual.

### 🔹 3. Teste Objetivo
> Verifica se o problema foi resolvido.

**Exemplo**: Se o agente alcançou o destino desejado ou resolveu o quebra-cabeça.

### 🔹 4. Função de Custo
> Mede o custo total de um caminho (em tempo, recursos, distância...).

**Exemplo**: Um GPS considera o tempo ou distância para sugerir a melhor rota.

---

## 🔍 Estratégias de Busca em IA

As estratégias de busca são usadas por agentes para encontrar **soluções** em um espaço de estados. Podemos dividi-las em dois grandes grupos:

### 🔹 1. **Buscas sem informação (cegas)**
São aquelas em que o agente **não tem conhecimento adicional** sobre o estado além das conexões entre eles. Ele explora o espaço de maneira sistemática.

---

### 🔸 **1.1 Busca em extensão (ou amplitude - Breadth-First Search)**

- Explora **todos os nós no mesmo nível** antes de avançar para o próximo.
- Garante encontrar a **solução mais próxima** (menor número de passos).
- Pode consumir muita memória.

**Exemplo de código**:
``` python
# 1.1 -> Breadth First Search
# FIFO
def bfs_2(graph, inital, goal):
    queue_2 = deque([(inital, [inital], 0)])

    while queue_2:
        node, result, cost = queue_2.popleft()

        if node == goal:
            return result, cost

        for neighbour, weight in graph.get(node, {}).items():
            if neighbour not in result:
                queue_2.append((neighbour, result + [neighbour], cost + weight))
    return None
```

📌 **Exemplo**: Procurar um contato na agenda telefônica nome por nome.

---

### 🔸 **1.2 Busca de custo uniforme (Uniform Cost Search)**

- Expande o **nó de menor custo total acumulado** primeiro.
- É ótima quando os custos de ações variam.
- Garante o **caminho de menor custo**, mas pode ser mais lenta.

**Exemplo de código:**
``` python
# 1.2 -> Uniform Cost Search
#priority queue
def ucs(graph, result, goal):
    queue = [(0, result, [])]
    visited = set()

    while queue:
        cost, node, path = heapq.heappop(queue)

        if node in visited:
            continue
        visited.add(node)

        path = path + [node]

        if node == goal:
            return path, cost

        for neighbour, weight in graph.get(node, {}).items():
            if neighbour not in visited:
                heapq.heappush(queue, (cost + weight, neighbour, path))
    return None
```
📌 **Exemplo**: Encontrar o caminho mais barato entre duas cidades.

---

### 🔸 **1.3 Busca em profundidade (Depth-First Search)**

- Explora **o caminho mais profundo** primeiro antes de voltar.
- Usa menos memória do que a busca em amplitude.
- Pode não encontrar a melhor solução ou até entrar em loop.

**Exemplo de código:**
``` python
# 1.3 ->  Depth First Search
# FIFO

def dfs(graph, result, goal):
    stack = [(result, [result], 0),]
    visited = set()


    while stack:
        node, path, cost = stack.pop()

        if node in visited:
            continue
        visited.add(node)

        if node == goal:
            return path, cost

        for neighbour, weight in graph.get(node, {}).items():
            if neighbour not in visited:
                stack.append((neighbour, path + [neighbour], cost + weight))
    return None
```
📌 **Exemplo**: Seguir um corredor de um labirinto até o fim antes de voltar.

---

### 🔸 **1.4 Busca em profundidade limitada**

- É como a busca em profundidade, **mas com um limite de profundidade**.
- Evita loops infinitos.
- Pode **falhar** se a solução estiver além do limite.

**Exemplo de código:**
```python
# 1.4 -> Depth Limitedd Search
def dls(graph, result, goal, limit, path=None, cost=0):
    if path is None:
        path = [result]

    if result == goal:
        return path, cost

    if limit <= 0:
        return None

    for neighbor, weight in graph.get(result, {}).items():
        if neighbor not in path:
            result = dls(graph, neighbor, goal, limit - 1, path + [neighbor], cost + weight)
            if result:
                return result
    return None
```
📌 **Exemplo**: Procurar uma chave caída em uma escada até 10 degraus abaixo.

---

### 🔸 **1.5 Busca de aprofundamento iterativo**

- Combina as vantagens da busca em **amplitude e profundidade**.
- Realiza buscas em profundidade com limites que aumentam gradualmente.
- Garante encontrar a solução ótima com **baixo uso de memória**.

**Exemplo de código:**
```python
# 1.5 -> Irative Deepening Depth First Search
def iddfs(graph, start, goal, max_depth=10):
    for depth in range(max_depth + 1):
        result= dls(graph, start, goal, depth)
        if result:
            return result
    return None
```
📌 **Exemplo**: Procurar item perdido em uma mochila por camadas (primeiro no topo, depois mais fundo, etc.).

---

### 🔸 1.6 **Busca Bidirecional (ou informada)**

- Parte do estado inicial e do objetivo simultaneamente.
- Reduz a complexidade de busca.
- Ex: Caminho entre duas cidades.

**Exemplo de código**
``` python
# 1.6 Bidirectional Search
def bidirectional_bfs(graph, start, goal):
    if start == goal:
        return [start], 0

    forward_queue = deque([(start, [start], 0)])
    backward_queue = deque([(goal, [goal], 0)])

    forward_visited = {start: (0, [start])}
    backward_visited = {goal: (0, [goal])}

    while forward_queue and backward_queue:
        
        node, path, cost = forward_queue.popleft()
        for neighbor, weight in graph.get(node, {}).items():
            if neighbor not in forward_visited:
                new_cost = cost + weight
                new_path = path + [neighbor]
                forward_visited[neighbor] = (new_cost, new_path)
                forward_queue.append((neighbor, new_path, new_cost))

                if neighbor in backward_visited:
                    back_cost, back_path = backward_visited[neighbor]
                    return new_path + back_path[::-1][1:], new_cost + back_cost

        node, path, cost = backward_queue.popleft()
        for neighbor, weight in graph.get(node, {}).items():
            if neighbor not in backward_visited:
                new_cost = cost + weight
                new_path = path + [neighbor]
                backward_visited[neighbor] = (new_cost, new_path)
                backward_queue.append((neighbor, new_path, new_cost))

                if neighbor in forward_visited:
                    front_cost, front_path = forward_visited[neighbor]
                    return front_path + new_path[::-1][1:], front_cost + new_cost

    return None, float('inf')  
```

📌 **Exemplo**: Usar a distância em linha reta até o objetivo como dica para guiar a busca.

---

---

## 🔹 2. Busca Heurística

A busca heurística é uma **estratégia informada**, ou seja, ela **usa conhecimento extra (uma heurística)** para tomar decisões mais inteligentes sobre qual caminho seguir.

---

### 🔸 2.1 Busca Gulosa (Greedy Best-First Search)

- Escolhe o **nó com menor valor heurístico**.
- **Rápida**, mas **não garante o menor custo**.
- Pode seguir por caminhos errados se a heurística não for boa.

**Exemplo de código:**
``` python
# 2.1 Greedy Best First Search

# problem algorithms Gredy Best First Search -> He need the heurisct value before the example

def greedy_best_first_search(graph, heuristics, start, goal):

    if start == goal:
        return [start]

    priority_queue = [(heuristics[start], start, [start], 0)]

    visited = set()

    while priority_queue:
        _, current_node, path, cost = heapq.heappop(priority_queue)

        if current_node == goal:
            return path, cost

        visited.add(current_node)

        for neighbor, weidth in graph.get(current_node, {}).items():
            if neighbor not in visited:
                new_path = path + [neighbor]
                new_cost = cost + weidth
                heapq.heappush(priority_queue, (heuristics[neighbor], neighbor, new_path, new_cost))
    return None
```

**Exemplo de heurística:**
``` python
heuristic = {
    "oradea": 380,
    "zerind": 374,
    "arad": 366,
    "sibiu": 253,
    "timisoara": 329,
    "lugoj": 244,
    "mehadia": 241,
    "drobeta": 242,
    "craiova": 160,
    "rimnicu_vilcea": 193,
    "fagaras": 178,
    "pitesti": 98,
    "bucharest": 0,
    "giurgiu": 77,
    "urziceni": 80,
    "hirsova": 151,
    "eforie": 161,
    "vaslui": 199,
    "iasi": 226,
    "neamt": 234
}
```

📌 **Exemplo**: Um GPS que sempre escolhe a rota com menor distância até o destino (em linha reta), sem considerar o trânsito.

---

### 🔸2.2 Busca A* (Busca em Estrela)

- Combina dois fatores:
  - `g(n)`: custo real até o nó `n`
  - `h(n)`: estimativa heurística até o objetivo
  - `f(n) = g(n) + h(n)`
- Garante o **melhor caminho possível** com heurística admissível.
- Muito usada em mapas, jogos e robótica.
- No melhor dos casos, deve-se utilizar de distância euclidiana

**Exemplo de coordenadas:**
```python
# 2.1 A *
coordinates = {
    "oradea": (1, 5),
    "zerind": (2, 6),
    "arad": (3, 4),
    "sibiu": (5, 5),
    "timisoara": (4, 2),
    "lugoj": (6, 3),
    "mehadia": (7, 2),
    "drobeta": (8, 1),
    "craiova": (9, 2),
    "rimnicu_vilcea": (7, 5),
    "fagaras": (8, 6),
    "pitesti": (10, 4),
    "bucharest": (12, 5),
    "giurgiu": (13, 3),
    "urziceni": (12, 6),
    "vaslui": (14, 7),
    "iasi": (13, 8),
    "neamt": (12, 9),
    "hirsova": (14, 5),
    "eforie": (15, 4)
}

def euclidean_distance(node1, node2):
    x1, y1 = coordinates[node1]
    x2,y2 = coordinates[node2]
    return math.sqrt((x2 - x1) **2 + (y2 - y1) **2)
```

**Exemplo de código:**
```python
def a_start_search_dynamic(graph, start, goal):
    priority_queue = [(euclidean_distance(start,goal), 0, start,[start])]
    heapq.heapify(priority_queue)
    visited = set()

    while priority_queue:
        f, g, current_node, path = heapq.heappop(priority_queue)

        if current_node == goal:
            return path, g
        if current_node in visited:
            continue
        visited.add(current_node)

        for neighbor, cost in graph[current_node].items():
            if neighbor not in visited:
                new_g = g + cost
                new_h = euclidean_distance(neighbor, goal)
                new_f = new_g + new_h
                heapq.heappush(priority_queue, (new_f, new_g, neighbor, path + [neighbor]))
    return None
```

📌 **Exemplo**: Um GPS que considera distância **e** tempo de deslocamento estimado.

---

## 📊 Tabela de Complexidade das Estratégias de Busca

| Estratégia                       | Completa | Ótima | Complexidade de Tempo | Complexidade de Espaço |
|----------------------------------|----------|--------|------------------------|-------------------------|
| Busca em largura (amplitude)     | Sim      | Sim    | O(b^d)                 | O(b^d)                  |
| Custo uniforme                   | Sim      | Sim    | O(b^(1 + [C*/ε]))      | O(b^(1 + [C*/ε]))       |
| Busca em profundidade            | Não      | Não    | O(b^m)                 | O(m)                    |
| Profundidade limitada            | Depende  | Não    | O(b^l)                 | O(bl)                   |
| Aprofundamento iterativo         | Sim      | Sim    | O(b^d)                 | O(bd)                   |
| Busca bidirecional               | Sim      | Sim    | O(b^(d/2))             | O(b^(d/2))              |
| Busca gulosa                     | Não      | Não    | O(b^m)                 | O(b^m)                  |
| Busca A*                         | Sim      | Sim*   | O(b^d)                 | O(b^d)                  |


 🔠Legenda dos Símbolos

- **b:** Fator de ramificação
    → Número médio de sucessores (filhos) por nó.

- **d:** Profundidade da solução ótima
    → Nível em que o objetivo pode ser encontrado pela primeira vez.

- **m:** Profundidade máxima do espaço de estados
    → Maior possível profundidade da árvore de busca (pode ser infinito).

- **C***: Custo do caminho da solução ótima
    → Soma dos custos das ações que levam até a meta, no menor caminho.

- **ε (épsilon):** Menor incremento de custo entre dois nós adjacentes
    → Usado na complexidade da busca de custo uniforme para garantir progresso.

---

