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
+ Java
  ```java
  do {
    /*
    Statments
    */
    System.out.println("Do you want to continue (y/n) :");
  } while( new Scanner(System.in).next().contains("y"));
  ```

+ Python
  ```python
  while True:
  	'''
  	Statments
  	'''
  	if 'y' not in input("Do you want to continue (y/n) : ") :
  		break
  ```
