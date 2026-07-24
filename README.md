XNOR Gate (Exclusive NOR)
Short Description:
The XNOR gate outputs a HIGH (1) signal when both inputs are the SAME (both 0 or both 1). It is the exact opposite of the XOR gate.

Your Truth Table (XNOR)
Switch 1	Switch 2	LED
UP (1)	UP (1)	ON
DOWN (0)	DOWN (0)	OFF
UP (1)	DOWN (0)	OFF
DOWN (0)	UP (1)	ON
How to Remember It
Rule	Meaning
XNOR = "Equality" Gate	Outputs HIGH when inputs are EQUAL
XNOR = NOT XOR	It's the opposite of XOR
XNOR = 1 when same	00 → 1, 11 → 1, 01 → 0, 10 → 0
Short Description for Your Notes
XNOR Gate (Exclusive NOR)

Output is ON (1) when both inputs are the same (both HIGH or both LOW)

Output is OFF (0) when inputs are different

Also called an "Equality Gate"

Symbol: XNOR or ⊙

Boolean Expression: Q = A ⊙ B or Q = NOT (A ⊕ B)

Truth Table:

A	B	Q
0	0	1
0	1	0
1	0	0
1	1	1
In Your Circuit (With UP = 1, DOWN = 0, LED ON = 1)
Switch 1 (A)	Switch 2 (B)	LED (Q)	Same?
UP (1)	UP (1)	ON (1)	 YES
DOWN (0)	DOWN (0)	OFF (0)	 YES
UP (1)	DOWN (0)	OFF (0)	 NO
DOWN (0)	UP (1)	ON (1)	 NO
What You Learned Today
By accidentally building an XNOR gate, you discovered:

XNOR = "Same" gate (LED ON when switches match)

XNOR is NOT XOR (XOR is ON when different)

XNOR = Inverted XOR

Bonus: XNOR vs XOR
Inputs	XOR (Different)	XNOR (Same)
0, 0	OFF (0)	ON (1)
0, 1	ON (1)	OFF (0)
1, 0	ON (1)	OFF (0)
1, 1	OFF (0)	ON (1)

