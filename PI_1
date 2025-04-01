data= (input("Qual é a data de hoje? "))
consumo_agua= float(input("Quantos litros de água você consumiu hoje? (aprox em litros): "))
energia_eletrica= float(input("Quantos kWh de energia elétrica você consumiu hoje?: "))
residuo= float(input("Quantos Kg de resíduos não recicláveis você gerou hoje?: "))
reciclados= float(input("Porcentagem de residuos reciclados no total(em %): v"))
print ("\n\t Quais meios de transporte você ultilizou hoje? ") #importante colocar pra responder com sim ou não? 
T_publico= (input("Transporte público(metro, ônibus, trem): "))
bicicleta= (input("Bicicleta: "))
caminhada= (input("Caminhada: ")) # type: ignore
carro= input (("Carro(combustíveis fósseis): "))
carro_eletrico= (input("Carros elétricos: "))
carona_compartilhada= (input("Caronas compartilhadas(combustível fóssil): "))
print ("\n Sustentabilidade")
 
if consumo_agua < 150:
    print("\n Consumo de água: Alta sustentabilidade.")
elif consumo_agua <= 200:
     print("\n Consumo de água: Moderada sustentabilidade.")
elif consumo_agua > 200:
      print("\n Consumo de água: Baixa sustentabilidade.")

if energia_eletrica < 5: 
     print("\n Consumo de energia: Alta sustentabilidade.")
elif energia_eletrica <= 10: 
      print("\n Consumo de energia: Moderada sustentabilidade.")
elif energia_eletrica > 10:
      print("\n Consumo de energia: Baixa sustentabilidade.")

x=100-reciclados
if x < 50:
     print ("\n Geração de resíduos não recicláveis: Alta sustentabilidade. ")
elif x >= 50: 
     print ("\n Geração de resíduos não recicláveis: Moderada sustentabilidade. ")
elif x > 20:
     print ("\n Geração de resíduos não recicláveis: Baixa sustentabilidade. ")

if bicicleta==("sim") or T_publico== ("sim") or carro_eletrico==("sim") or caminhada==("sim"): 
     print ("\n Transporte: ALta sustentabilidade")
else: 
     print("\n Tranporte: Baixa sustentabilidade. ")
if (carro==("sim") or carona_compartilhada==("sim") ) and (T_publico==("sim") or bicicleta==("sim") or caminhada==("sim") or carro_eletrico==("sim")):
     print("\n Transporte: Moderada sustentabilidade. ")