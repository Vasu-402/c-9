int main() {
    int i,j,n;
    printf("enter the row of the matrix:");
    scanf("%d",&n);
    for(int i=1;i<=n;i++)
    {
      for(int j=1;j<=i;j++)
      {
          if(i==1||i==j||j==n)
          {
              printf("* ");
          }
          else 
          {
              printf("  ");
          }
      }
      printf("\n");
    }
    return 0;
}
