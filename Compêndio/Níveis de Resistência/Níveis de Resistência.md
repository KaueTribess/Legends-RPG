### Descrição
Níveis de Resistência determinam como e quanto um personagem ou objeto é afetado por um [[Definição de Dano|Dano]] ou [[Condições|Condição]] específicos.

### Níveis
- [[Vulnerável]]:
	- **Dano:** ×2. 
	- **Condição:** [[Desvantagem]].
- [[Neutro]]:
	- **Dano:** ×1. 
	- **Condição:** Normal.
- [[Resistente]]:
	- **Dano:** ÷2. 
	- **Condição:** [[Vantagem]].
- [[Imune]]:
	- **Dano:** Anulado. 
	- **Condição:** Não aplicada.

### Contra dano
Cada instância de dano consulta os níveis correspondentes ao seu [[Tipos de Dano|Tipo]] e à sua [[Naturezas de Dano|Natureza]] seguindo estes passos:

1. **Verifique Imunidade:** 
   Se o nível de resistência ao Tipo ou à Natureza corresponder a [[Imune]], o dano é anulado.
2. **Compense os níveis:** 
   Cada [[Vulnerável]] acrescenta **1 nível** e cada [[Resistente]] remove **1 nível**.
3. **Aplique o resultado:** 
   O dano final fica limitado a **metade**, **normal** ou **dobro** do valor original.

> Uma instância de dano [[Verdadeiro]] não possui [[Naturezas de Dano|Natureza]] e ignora Níveis de Resistência, ele não pode ser dobrado, reduzido nem anulado por eles.

### Contra Condições
O nível se aplica à rolagem usada para aplicar a [[Condições|Condição]], seja ela de uma magia, habilidade, ataque ou qualquer outra fonte, seguindo estes passos:

1. **Verifique Imunidade:** 
   Se o nível de resistência à Condição corresponder a [[Imune]], a Condição não é aplicada.
2. **Aplique o resultado:** 
   A rolagem final é feita com [[Desvantagem]], neutra ou [[Vantagem]].

> Se a Condição exigir rolagens internas para resistir a ela, essas rolagens recebem a mesma [[Vantagem]] ou [[Desvantagem]].
