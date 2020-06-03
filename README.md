# Descrição

Uma lista de tarefas tem várias tarefas associadas. Cada lista de tarefas pertence a um utilizador. O utilizador pode criar, procurar, listar, alterar, e remover as tarefas de uma lista. O utilizador também pode criar, procurar, e remover listas de tarefas.
Cada lista de tarefas tem um nome único. Cada tarefa tem uma descrição e um identificador único dentro da lista à qual pertence. Cada utilizador tem um nome único. Pretende-se tornar a procura de informação o mais eficiente possível.

# Comandos

    CU Criar utilizador
        CU UserName

    LU Listas utilizadores
        LU

    DU Elimina utilizador
        DU UserName

    CTL Criar lista de tarefas
        CTL UserName TaskListName

    CT Criar tarefa em lista de tarefas
        CT UserName TaskListName TaskId TaskDescription

    DT Elimina tarefa de lista de tarefas
        DT UserName TaskListName TaskId

    ET Altera a descrição de uma tarefa de lista de tarefas
        ET Username TaskListName TaskId Description

    LTL Listar listas de tarefas de utilizador
        LTL UserName

    LTTL Listas tarefas de lista de tarefas
        LTTL UserName TaskListName

    CTS Altera o estado da tarefa
        CTS UserName TaskListName TaskId

    S Grava o estado da aplicação
        S Filename
    
    L Carrega o estado da aplicação
        L Filename

    Linha vazia - termina
