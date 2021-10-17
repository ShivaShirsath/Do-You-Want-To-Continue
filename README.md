# Do You Want To Continue
+ C
  ```c
  char continue;
  do {
    /*
     Statements
     */
    printf("\nDo you want to continue (y/n) ? ");
    scanf("%s", &c);
  } while ( continue == 'y' || continue == 'Y' );
  ```
+ C++
  ```cpp
  char continue;
  do {
    /*
     Statements
     */
    cout << "\nDo you want to continue (y/n) ? " ;
    cin >> c ;
  } while ( continue == 'y' || continue == 'Y' );
  ```
