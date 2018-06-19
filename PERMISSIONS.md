# Permissões

O sistema de Permissões é uma framework administrativa da UFABC.Dojo, cujo objetivo é delinear as atribuições funcionais, legais e pragmáticas dos membros da entidade, e da comunidade externa.

## Lista de Permissões
|  ID  | Char Identificador | Nome | Descrição |
|:----:|:------------------:|:-----|:---------:|
| 0    |                    | Nenhuma Permissão | Você não tem nenhum direito. |
| 1    | p                  | Projetos | Você pode criar projetos/grupos-de-estudos, desde que haja um(a) ou mais membros(as) involvidos(as) |
| 2    | P                  | Projetos++ | Você pode criar projetos independentemente |
| 4    | t                  | Tutoria | Você pode ser um(a) tutor(a) de membros(as) ingressantes |
| 8    | b                  | Ban | Você possui o Ban Hammer (Comunidade + Membros) |
| 16   | $                  | Dinheiro | Você tem direito de administrar o capital financeiro da Entidade |
| 32   | r                  | Representatividade | Você é um(a) porta-voz da Entidade, e pode administrar permissões |
| 64   | e                  | Espaço Físico | Você pode efetuar reservas de espaços físicos em nome da Dojo |
| 128  | s                  | Redes Sociais | Você pode administrar as mídias sociais da Dojo |
| 256  | c                  | Code Challenge | Você pode presidir a Code Challenge |
| 1048576 | &               | Cardu | Você tem o direito de ser o(a) Cardu |
| 2097152 | ¬               | NPC | Você tem o direito de ser um(a) NPC. _oi edu_ |

**Protip**: para descobrir o valor hex da permissão total, basta somar os IDs e converter o resultado para hexadecimal. 

**Protip⁻¹:** para descobrir se o(a) membro(a) X possui permissão Y, use um bitwise OR entre a  permissão total e o ID da permissão em questão. Se o resultado for diferente de zero, o(a) membro(a) tem a permissão.

**Protip 2**: use o conversor no [site da Entidade](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
 
## Lista de Membros e Permissões
| Membro | Permissão (texto) | Permissão (hex) |
|:------:|:-----------------:|:---------------:|
| Cardu  | +pPt$res¬         | 0x2000F7        |
| Edu    | +pPtbrs&          | 0x1000AF        |
| Wesley | +pPtb$resc        | 0x1FF           |
 
