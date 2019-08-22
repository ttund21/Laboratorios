# Laboratórios

## COMANDOS UTEIS

#### 1. Iniciando o VagrantFile.
+ $ vagrant up --provision --> Vai executar o Vagrantfile e o **--provision** vai executar o shell script que está dentro do Vagrantfile, uso quando vou executar o Vagrantfile pela primeira vez;
+ $ vagrant up --no-provision --> Vai executar o Vagrantfile e o **--no-provision** não vai executar o shell script que está dentro do Vagrantfile, uso quando o o status da máquina está em **poweroff**.

#### 2. Desligar.
+ $ vagrant halt 

#### 3. Destruir.
+ $ vagrant destroy

#### 4. Provisionar o shell script.
+ $ vagrant provision

#### 5. Atualizar alterações no Vagrantfile.
+  $ vagrant reload

#### 6. Ver o status da máquina.
+ $ vagrant status
