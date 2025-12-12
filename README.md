# Resumo-De-Lab
Resumo das lições aprendidas no laboratorio da faculdade

Foi aprendido:

- Como criar maquinas virtuais utilizando o microsoft azure
  
  Seleção da assinatura(Forma de pagamento), Grupo de recursos(Grupo onde ficarão as redes utilizadas pelas máquinas), Seleção da zona(Datacenter onde será hospedado a máquina), Região onde a maquina será hospedada.
  
  <img width="408" height="226" alt="image" src="https://github.com/user-attachments/assets/62df3bf5-c37a-4552-9c1e-c5efd36173f8" />

  seleção da imagem(Sistema operacional), arquitetura de VM(em que formato os aplicativos serão instalados), seleção do Tamanho(hardware da maquina)

  <img width="412" height="115" alt="image" src="https://github.com/user-attachments/assets/c40f5a0f-67d4-434d-b362-45bf60d16d2f" />

  Login e senha para acessar a maquina remotamente, seleção de portas de entrada para acessar a maquina.

  <img width="397" height="199" alt="image" src="https://github.com/user-attachments/assets/c44a7ce0-060c-4e50-a2ce-c75744cbbadd" />

  Rede que será utilizada pela maquina, sub-rede utilizada pela maquina, ip publico para poder ser acessada por outras maquinas

  <img width="395" height="115" alt="image" src="https://github.com/user-attachments/assets/76f6eab0-ea51-444a-a446-1f510a26ae26" />

  # Teste de conexão entre duas maquinas

  pingando a maquina 2 pela maquina 1

  <img width="363" height="112" alt="image" src="https://github.com/user-attachments/assets/d82ff8b0-40a3-4bc0-8a53-8b571892c33b" />

  pingando a maquina 1 pela maquina 2

  <img width="349" height="122" alt="image" src="https://github.com/user-attachments/assets/3a91362d-3c19-4d47-a3eb-8df432679a75" />

- como criar redes usando o microsoft azure
  
  Seleção da assinatura(forma de pagamento), Grupo de recursos(Grupo onde ficarão as redes utilizadas pelas máquinas), nome da rede, região onde ela estara localizada.

  <img width="390" height="197" alt="image" src="https://github.com/user-attachments/assets/06ebf52d-f70f-4ea1-834b-69c975b86b29" />

  criptografia de rede virtual que é utilizada para criptografar o tráfego(opcional), azure Bastion que é utilizado para as maquinas se conectarem sem a necessidade de um ip publico(opcional).

   <img width="385" height="173" alt="image" src="https://github.com/user-attachments/assets/e7d6492d-56c7-4d8e-81a3-ac9bd1c8117e" />

   Firewall do azure(utilizado para proteger a rede), proteção contra DDoS(fornece uma mitigação contra ataques DDoS).

   <img width="380" height="179" alt="image" src="https://github.com/user-attachments/assets/4f772224-221f-429f-82d1-386bfe71f181" />



- Como funcionam as zonas e o porque delas serem importantes

  As zonas são uma funcionalidade fornecida pela Microsft Azure para proteger contra interrupções relacionadas a infraestrutura, deixando disponivel 3 zonas em cada região, para quando uma parar de funcionar as outras duas possam continuar com a aplicação.

  <img width="370" height="162" alt="image" src="https://github.com/user-attachments/assets/aa9ed0e7-9b40-401e-bf5e-b135b4fc721c" />




