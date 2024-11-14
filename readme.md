<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Prompt solicitado ao modelo Claude Sonnet 3.5:
"Observe o arquivo .md do repositório clonado em https://github.com/Masteradilio/prompt-challenger-personal-ia. 
Crie para mim um sistema em python que faça o que é proposto no repositório mas com algumas funcionalidades a mais, para que fique mais completo."

Resposta retornada pelo modelo:

Com base no repositório fornecido, vou criar um sistema em Python mais completo para um assistente de personal trainer. Aqui está o código:

'''
import json
from datetime import datetime
import os

class PersonalTrainerAssistant:
  def __init__(self):
      self.biotypes = {
          "ectomorfo": "Corpo mais magro, difícil ganhar peso e massa muscular",
          "mesomorfo": "Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura",
          "endomorfo": "Corpo com tendência a acumular gordura, maior dificuldade em perder peso"
      }
      
      self.training_days = {
          1: "Full Body",
          3: "ABC",
          5: "ABCDE"
      }
      
      self.exercise_types = {
          "funcional": "Exercícios que melhoram a funcionalidade do corpo",
          "maquinario": "Exercícios feitos em máquinas",
          "peso_livre": "Exercícios com pesos livres",
          "cardio": "Exercícios voltados para resistência cardiovascular",
          "hiit": "Treinos intervalados de alta intensidade"
      }
      
      self.users = {}

  def cadastrar_usuario(self):
      print("\n=== Cadastro de Usuário ===")
      nome = input("Nome: ")
      idade = int(input("Idade: "))
      peso = float(input("Peso (kg): "))
      altura = float(input("Altura (m): "))
      
      print("\nBiotipos disponíveis:")
      for biotipo in self.biotypes.keys():
          print(f"- {biotipo}")
      biotipo = input("Seu biotipo: ").lower()
      
      print("\nDias disponíveis para treino:")
      for dias in self.training_days.keys():
          print(f"- {dias} dia(s)")
      dias_treino = int(input("Quantidade de dias: "))
      
      print("\nTipos de exercícios disponíveis:")
      for tipo in self.exercise_types.keys():
          print(f"- {tipo}")
      tipo_exercicio = input("Tipo preferido: ").lower()
      
      objetivos = input("\nQuais são seus objetivos? ")
      
      usuario = {
          "nome": nome,
          "idade": idade,
          "peso": peso,
          "altura": altura,
          "biotipo": biotipo,
          "dias_treino": dias_treino,
          "tipo_exercicio": tipo_exercicio,
          "objetivos": objetivos,
          "imc": round(peso / (altura ** 2), 2),
          "data_cadastro": datetime.now().strftime("%d/%m/%Y"),
          "treinos_gerados": []
      }
      
      self.users[nome] = usuario
      self.salvar_usuarios()
      print("\nUsuário cadastrado com sucesso!")
      return usuario

  def gerar_treino(self, usuario):
      print("\n=== Gerando Treino Personalizado ===")
      
      treino = {
          "data": datetime.now().strftime("%d/%m/%Y"),
          "tipo": self.training_days[usuario["dias_treino"]],
          "exercicios": self._gerar_exercicios(usuario),
          "recomendacoes": self._gerar_recomendacoes(usuario)
      }
      
      usuario["treinos_gerados"].append(treino)
      self.salvar_usuarios()
      return treino

  def _gerar_exercicios(self, usuario):
      exercicios = {}
      
      if usuario["dias_treino"] == 1:  # Full Body
          exercicios["Dia 1"] = [
              "Agachamento 4x12",
              "Supino 4x12",
              "Remada 4x12",
              "Desenvolvimento 4x12",
              "Extensão de Tríceps 3x15",
              "Rosca Direta 3x15",
              "Prancha 3x45s"
          ]
          
      elif usuario["dias_treino"] == 3:  # ABC
          exercicios["Dia A - Peito/Tríceps"] = [
              "Supino Reto 4x12",
              "Supino Inclinado 4x12",
              "Extensão de Tríceps 4x12",
              "Tríceps Corda 3x15"
          ]
          exercicios["Dia B - Costas/Bíceps"] = [
              "Puxada Frontal 4x12",
              "Remada Baixa 4x12",
              "Rosca Direta 4x12",
              "Rosca Martelo 3x15"
          ]
          exercicios["Dia C - Pernas/Ombros"] = [
              "Agachamento 4x12",
              "Leg Press 4x12",
              "Desenvolvimento 4x12",
              "Elevação Lateral 3x15"
          ]
          
      else:  # ABCDE
          exercicios["Dia A - Peito"] = [
              "Supino Reto 4x12",
              "Supino Inclinado 4x12",
              "Crucifixo 3x15"
          ]
          exercicios["Dia B - Costas"] = [
              "Puxada Frontal 4x12",
              "Remada Baixa 4x12",
              "Pulldown 3x15"
          ]
          exercicios["Dia C - Pernas"] = [
              "Agachamento 4x12",
              "Leg Press 4x12",
              "Extensão 3x15"
          ]
          exercicios["Dia D - Ombros"] = [
              "Desenvolvimento 4x12",
              "Elevação Lateral 4x12",
              "Elevação Frontal 3x15"
          ]
          exercicios["Dia E - Braços"] = [
              "Rosca Direta 4x12",
              "Extensão de Tríceps 4x12",
              "Rosca Martelo 3x15"
          ]
          
      return exercicios

  def _gerar_recomendacoes(self, usuario):
      recomendacoes = []
      
      # Recomendações baseadas no biotipo
      if usuario["biotipo"] == "ectomorfo":
          recomendacoes.append("Foque em exercícios compostos com cargas pesadas")
          recomendacoes.append("Aumente a ingestão calórica")
      elif usuario["biotipo"] == "mesomorfo":
          recomendacoes.append("Mantenha um equilíbrio entre exercícios de força e cardio")
          recomendacoes.append("Mantenha uma dieta balanceada")
      else:  # endomorfo
          recomendacoes.append("Inclua mais exercícios cardiovasculares")
          recomendacoes.append("Controle a ingestão calórica")
          
      # Recomendações baseadas no IMC
      if usuario["imc"] < 18.5:
          recomendacoes.append("Procure aumentar o peso de forma saudável")
      elif usuario["imc"] > 25:
          recomendacoes.append("Foque na perda de gordura com exercícios aeróbicos")
          
      return recomendacoes

  def visualizar_usuario(self, nome):
      if nome in self.users:
          usuario = self.users[nome]
          print("\n=== Dados do Usuário ===")
          for key, value in usuario.items():
              if key != "treinos_gerados":
                  print(f"{key.replace('_', ' ').title()}: {value}")
          
          if usuario["treinos_gerados"]:
              print("\nÚltimo treino gerado:")
              ultimo_treino = usuario["treinos_gerados"][-1]
              print(f"\nData: {ultimo_treino['data']}")
              print(f"Tipo: {ultimo_treino['tipo']}")
              
              print("\nExercícios:")
              for dia, exercicios in ultimo_treino["exercicios"].items():
                  print(f"\n{dia}:")
                  for ex in exercicios:
                      print(f"- {ex}")
              
              print("\nRecomendações:")
              for rec in ultimo_treino["recomendacoes"]:
                  print(f"- {rec}")
      else:
          print("Usuário não encontrado!")

  def salvar_usuarios(self):
      with open('usuarios.json', 'w') as f:
          json.dump(self.users, f)

  def carregar_usuarios(self):
      if os.path.exists('usuarios.json'):
          with open('usuarios.json', 'r') as f:
              self.users = json.load(f)

def main():
  assistant = PersonalTrainerAssistant()
  assistant.carregar_usuarios()
  
  while True:
      print("\n=== Menu Principal ===")
      print("1. Cadastrar novo usuário")
      print("2. Gerar treino")
      print("3. Visualizar usuário")
      print("4. Sair")
      
      opcao = input("\nEscolha uma opção: ")
      
      if opcao == "1":
          assistant.cadastrar_usuario()
      elif opcao == "2":
          nome = input("Nome do usuário: ")
          if nome in assistant.users:
              treino = assistant.gerar_treino(assistant.users[nome])
              print("\nTreino gerado com sucesso!")
          else:
              print("Usuário não encontrado!")
      elif opcao == "3":
          nome = input("Nome do usuário: ")
          assistant.visualizar_usuario(nome)
      elif opcao == "4":
          print("Encerrando programa...")
          break
      else:
          print("Opção inválida!")

if __name__ == "__main__":
  main()
'''

Este sistema inclui as seguintes funcionalidades adicionais:

Sistema completo de cadastro de usuários com persistência de dados em arquivo JSON

1. Cálculo de IMC automático
2. Histórico de treinos gerados
3. Recomendações personalizadas baseadas no biotipo e IMC
4. Interface de menu interativa
5. Treinos detalhados para diferentes frequências de treino (1, 3 ou 5 dias)
6. Visualização completa dos dados do usuário e último treino gerado
7. Salvamento automático das informações

Para usar o sistema, basta executar o script e seguir as opções do menu. O sistema permite cadastrar múltiplos usuários, gerar treinos personalizados e visualizar as informações cadastradas.
