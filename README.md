# Sistema de Hospedagem em C#
![.NET](https://img.shields.io/badge/.NET-8-blue)
![C#](https://img.shields.io/badge/C%23-Orientação_a_Objetos-brightgreen)

Este repositório é um fork do desafio da DIO, focado em práticas de C# e orientação a objetos.

## Funcionalidades implementadas
- ✅ Validação da capacidade da suíte: impede reservas com número de hóspedes maior que a capacidade.
- ✅ Método `ObterQuantidadeHospedes` retorna a quantidade total de hóspedes de uma reserva.
- ✅ Método `CalcularValorDiaria` calcula o valor da reserva, aplicando **10% de desconto** para reservas com 10 dias ou mais.

## Estrutura do projeto
- **Pessoa.cs**: representa o hóspede.
- **Suite.cs**: representa a suíte do hotel, incluindo capacidade e valor da diária.
- **Reserva.cs**: faz o relacionamento entre Pessoa e Suíte, realizando cálculos de quantidade de hóspedes e valor da diária.
- **Program.cs**: arquivo principal para testar as funcionalidades implementadas.

![Diagrama de classes do hotel](diagrama_classe_hotel.png)

## 📌 Como rodar

1. Clone o repositório:

   ```bash
   git clone https://github.com/andreza1freitas/trilha-net-explorando-desafio.git

2. Navegue até o diretório do projeto:

   ```bash
   cd trilha-net-explorando-desafio

3. Restaure os pacotes NuGet necessários:

   ```bash
   dotnet restore DesafioProjetoHospedagem.csproj

4. Compile o projeto:

   ```bash
   dotnet build DesafioProjetoHospedagem.csproj

5. Execute o projeto:

   ```bash
   dotnet run --project DesafioProjetoHospedagem.csproj
<br> 

### Observações
- Implementações próprias destacando validação de capacidade e cálculo de diária com desconto.
- Projeto utiliza **.NET 8**; recomenda-se ter a versão mais recente do SDK instalada.

### 📜 Licença
Projeto criado para estudo e prática educacional, sem fins comerciais.








