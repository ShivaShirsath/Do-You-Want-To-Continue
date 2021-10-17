# Do You Want To Continue
+ C
  ```c
  char c;
  do {
    /*
     Statements
     */
    printf("\nDo you want to continue (y/n) ? ");
    scanf("%s", &c);
  } while ( c == 'y' || c == 'Y' );
  ```
+ C++
  ```cpp
  char c;
  do {
    /*
     Statements
     */
    cout << "\nDo you want to continue (y/n) ? " ;
    cin >> c ;
  } while ( c == 'y' || c == 'Y' );
  ```
+ Java
  ```java
  do {
    /*
    Statments
    */
    System.out.println("Do you want to continue (y/n) :");
  } while( new Scanner(System.in).next().contains("y") );
  ```

+ Python
  ```python
  while True :
  	'''
  	Statments
  	'''
  	if 'y' not in input("Do you want to continue (y/n) : ") :
  		break
  ```
