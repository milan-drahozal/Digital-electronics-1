# Digital-eletronics-1

## Labs

### Domácí práce z 1. cvičení
*Příklad textu psaný kurzívou.* **Text psaný tučným písmem.** ***Kombinace obou metod.***    ~~Chybný text.~~

1. Potraviny
2. Kosmetika
3. Oblečení
     1. Mikina
      2. Tričko
      3. Vesta
* Převést zboží
* Koupit nářadí
  * šroubovák
  * kladivo
  
 http://github.com - automatic!
[GitHub](http://github.com)

https://www.edaplayground.com/x/DjZa - automatic!
[EDAplayground](https://edaplayground.com/x/DjZa)
  
| c | b | a | f(c,b,a,)|
|---|---|---|----------|
| 0 | 0 | 0 |          |
| 0 | 0 | 1 |          |
| 0 | 1 | 0 |          |
| 0 | 1 | 1 |          |
| 1 | 0 | 0 |          |
| 1 | 0 | 1 |          |
| 1 | 1 | 0 |          |
| 1 | 1 | 1 |          |


**Source code**

```vhdl
architecture testbench of tb_gates is

    -- Local signals
    signal s_a    : std_logic;
    signal s_b    : std_logic;
    signal s_for  : std_logic;
    signal s_fand : std_logic;
    signal s_fxor : std_logic;

begin
    -- Connecting testbench signals with gates entity (Unit Under Test)
    uut_gates : entity work.gates
        port map(
            a_i    => s_a,
            b_i    => s_b,
            for_o  => s_for,
            fand_o => s_fand,
            fxor_o => s_fxor
        );
```
**Tajný vzkaz**
