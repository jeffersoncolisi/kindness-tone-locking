# kindness-tone-locking

O sistema precisa calcular um Índice Composto de Drift (D_t) em tempo real, comparando o turno candidato atual (y_t) contra uma janela móvel de referência dos últimos turnos aprovados (H_{t-k:t-1}) e contra o vetor-âncora da persona (P_0).