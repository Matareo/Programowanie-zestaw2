```c

https://inf.ug.edu.pl/~tdz/C/lab-zadania2wer2.pdf

ZAD1

#include <stdio.h>

int main() {

  int tab[]={1,3,7,8,9};
  int i;

  for(i=0;i<=4; i=i+1) printf("tab[%d]=%d\n",i, tab[i]);

  return 0;

  }
  
  
ZAD2

#include <stdio.h>

int main() {

  int tab[]={1,3,7,8,9};
  int i;

  for(i=4;i>=0; i=i-1) printf("tab[%d]=%d\n",i, tab[i]);

  return 0;

  }
  
  
ZAD3

#include <stdio.h>

int main() {

  int tab[]={1,3,7,8,9};
  int i,k;
  k=1;

  for(i=0;i<=4; i++)
    {k=k*2;
      tab[i]=k;
printf("tab[%d]=%d\n",i, tab[i]);
    }
  return 0;

  }
  

ZAD4

#include <stdio.h>
int main()
{
	int tab[5], i;
	for(i=0;i<=4;i=i++)
		{
			printf("Podaj wartość dla tab[%d]=", i);
			scanf("%d", &tab[i]);
}
for(i=0;i<=4;i=i+1)
	printf("tab[%d]=%d\n",i, tab[i]);

return 0;
}


ZAD5

#include <stdio.h>
int main()
{
	int tab[5], i;
	for(i=0;i<=4;i=i++)
		{
			printf("Podaj wartość dla tab[%d]=", i);
			scanf("%d", &tab[i]);
}
for(i=4;i>=0;i=i-1)
	printf("tab[%d]=%d\n",i, tab[i]);

return 0;
}


http://wbzyl.inf.ug.edu.pl/c/budowanie-programow
od 6 do 9
