```c
int dzialanie(int a, int b, char c, int q){
  switch(c){
  case '-':
    q=a-b;
    break;
  case'+':
    q=a+b;
    break;
  case'*':
    q=a*b;
    break;
  case'/':
    q=a/b;
    break;
  }
}
main()
{
  int x;
  int y;
  printf("Podaj pierwsza liczbe:\n");
  scanf("%d",&x);
  printf("Podaj druga liczbe:\n");
  scanf("%d",&y);
  char z;
  printf("Podaj znak:\n");
  scanf("%s",&z);
  int k;
  printf("Liczba %d i %d da nam %d",dzialanie(x,y,z,k));
}

