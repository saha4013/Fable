# Fable
#include <stdio.h>
int main()
{
   printf("import copy);

queue = [143, 86, 1470, 913, 1774, 948, 1509, 1022, 1750, 130];
t = copy.copy(queue);
total = 0;
direction = 1;
curr = t.pop(0);
seq = [curr];
while len(t)>0:
    curr += direction;
    total += 1;
    if curr in t:
        t.remove(curr);
        seq.append(curr);
    if curr == 4999:
        direction = -1;
    if curr == 0:
        direction = 1;
printf("t. SCAN:\", total, seq
\n");
      return 0;
}
