# Plano de Implantação - Postiz (smlab)

Este plano descreve os passos para implantar a aplicação Postiz como uma stack no Portainer, utilizando Docker Swarm e Traefik.

- [ ] **1. Preparar Ambiente no Portainer:**
  - [ ] Criar a rede externa `altrs_net` (se ainda não existir).
  - [ ] Criar os volumes externos:
    - `smlab_postgres_data`
    - `smlab_redis_data`
    - `smlab_config`
    - `smlab_uploads`

- [ ] **2. Criar a Stack:**
  - [ ] Copiar o conteúdo do arquivo `smlab-stack.yml`.
  - [ ] No Portainer, ir para "Stacks", clicar em "Add stack".
  - [ ] Dar o nome de `smlab`.
  - [ ] Colar o conteúdo no "Web editor".
  - [ ] Clicar em "Deploy the stack".

- [ ] **3. Verificar a Implantação:**
  - [ ] Acessar a URL `https://smlab.arelis.online` para verificar se a aplicação está no ar.
  - [ ] Verificar os logs dos serviços no Portainer para garantir que não há erros.
