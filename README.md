# **ARRAYS LETTER B**

# Information

* **Program to print "B" with "star" using multidimensional arrays.**

# Technologies Used

* **JAVA**

# Contents

* The variables **int** and **String** are defined.

* The array numbers were determined according to the letter drawing in the table.

* The letter B was formed using the i and j variables and the star symbol.

<br />

# Codes

```Java

        public class ArraysLetterB {

            public static void main(String[] args) {

                String[][] letter = new String[7][4];


```

```Java

                for(int i = 0; i < letter.length; i++){

                    for(int j = 0; j < letter[i].length; j++){

                        if(i == 0 || i == 3 || i == 6){

                            letter[i][j] = " * ";

                        }else if(j == 0 || j == 3){

                            letter[i][j] = " * ";

                        }else{

                            letter[i][j] = "   ";

                        }
                    }
                }

                for(String[] row : letter){

                    for(String col : row){

                        System.out.print(col);

                    }
                    System.out.println();
                }
            }
        }

```

```bash

     *  *  *  *
     *        *
     *        *
     *  *  *  *
     *        *
     *        *
     *  *  *  *

```

<br />

# LINK

* Click here https://github.com/Fogo9/ArraysLetterB.git to access the Github page for this project.

<br />

# LICENSE

* This software is licensed By Tuncay Demir under the MIT license.

<br />

>[Patika.dev](https://app.patika.dev/fogomurphy)

<br/>

| Name |  Email |
| ---- |  ----- |
| Tuncay | tuncaydemir682@gmail.com |
