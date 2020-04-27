Test code to explore how to change RGB LED colours on the HyperX Alloy FPS RGB keyboard.

compile : 
gcc test.c -lusb-1.0 -o test
gcc select.c -lusb-1.0 -o select

Run :
Set LED colours :
./test <profile> <RED> <GREEN> <BLUE> 13 29 45 77 125 141 21 127 23 39 55 133 149 148 12 28 44 60 76 92 108 124 140 20 36 52 111 143 85 101 117 148 11 27 43 59 75 91 107 123 139 19 35 51 22 129 145 69 132 10 26 42 58 74 90 106 122 138 18 34 50 126 38 63 79 95 65 81 97 132 9 25 41 57 73 89 105 121 137 17 33 49 15 47 78 94 110 68 84 100 116 8 24 40 56 72 88 104 120 136 16 32 48 14 30 46 62

Change active profile :
./select <profile>

profile : 1 to 4


