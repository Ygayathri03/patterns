# pattern 1 
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
for(int i=0;i<n;i++){
  for(int j=0;j<n;j++){
    cout<<"* ";
    }
  cout<<endl;
}

# pattern 2
* 
* * 
* * * 
* * * * 
* * * * *
for(int i=0;i<n;i++){
  for(int j=0;j<=i;j++){
    cout<<"* ";
    }
  cout<<endl;
}

# patter 3
1
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
for(int i=0;i<n;i++){
  for(int j=0;j<=i;j++){
    cout<<j+1<<" ";
    }
  cout<<endl;
}

# pattern 4
1
2 2 
3 3 3 
4 4 4 4 
5 5 5 5 5
for(int i=0;i<n;i++){
  for(int j=0;j<=i;j++){
    cout<<i+1<<" ";
    }
  cout<<endl;
}

# pattern 5
* * * * *
* * * * 
* * * 
* *  
*
for(int i=0;i<n;i++){
  for(int j=0;j<n-i;j++){
    cout<<"* ";
    }
  cout<<endl;
}

# pattern 6
1 2 3 4 5
1 2 3 4
1 2 3 
1 2  
1 
for(int i=0;i<n;i++){
  for(int j=0;j<n-i;j++){
    cout<<j+1<<" ";
    }
  cout<<endl;
}

# pattern 7
    *
   ***  
  *****
 *******
*********
for(int i=0;i<n;i++){
  for(int j=1;j<n-i;j++){
    cout<<" ";
    }
  for(int j=0;j<((2*i)+1);j++){
    cout<<"*";
    }
  cout<<endl;
}

# pattern 8
*********
 *******
  *****
   ***
    *
for(int i=0;i<n;i++){
  for(int j=0;j<i;j++){
    cout<<" ";
    }
   for(int j=0;j<((2*n)-((2*i)+1));j++){
    cout<<"*";
    }
  cout<<endl;
}

# pattern 9
    *
   * *
  * * *
 * * * *
* * * * *
* * * * *
 * * * *
  * * *
   * *
    *
for(int i=0;i<n;i++){
  for(int j=1;j<n-i;j++){
    cout<<" ";
    }
  for(int j=0;j<=i;j++){
    cout<<"* ";
    }
  cout<<endl;
}
for(int i=0;i<n;i++){
  for(int j=0;j<i;j++){
    cout<<" ";
    }
   for(int j=0;j<2*n - n-i;j++){
    cout<<"* ";
    }
  cout<<endl;
}

# pattern 10
* 
* * 
* * * 
* * * * 
* * * * *
* * * *
* * *
* *
*
for(int i=0;i<n;i++){
  for(int j=0;j<=i;j++){
    cout<<"* ";
    }
  cout<<endl;
}
for(int i=0;i<n;i++){
  for(int j=0;j<n-i-1;j++){
    cout<<"* ";
    }
  cout<<endl;
}

# pattern 11
1 
0 1 
1 0 1
0 1 0 1 
1 0 1 0 1
for(int i=0;i<n;i++){
int start=1;
  if(i%2==0) start=1;
  else start=0;
  for(int j=0;j<=i;j++){
  cout<<start<<" ";
  start=1-start;
  }
  cout<<endl;
}

# pattern 12
1                 1
1 2             2 1
1 2 3         3 2 1
1 2 3 4     4 3 2 1
1 2 3 4 5 5 4 3 2 1
for(int i=0;i<n;i++){
  for(int j=0;j<=i;j++){
    cout<<j+1<<" ";
    } 
  for(int j=0;j<2*n - 2*(i+1);j++){
  cout<<"  ";
  }
  int x=i+1;
  for(int j=0;j<=i;j++){
  cout<<x<<" ";
  x--;
  }
  cout<<endl;
}

# pattern 13
1 
2 3 
4 5 6 
7 8 9 10 
11 12 13 14 15
int x=1;
for(int i=0;i<n;i++){
  for(int j=0;j<=i;j++){
    cout<<x<<" ";
    x++;
    }
  cout<<endl;
}

# pattern 14
A
AB
ABC
ABCD
ABCDE
for(int i=0;i<n;i++){
  char x='A';
  for(int j=0;j<=i;j++){
    cout<<x;
    x++;
    }
  cout<<endl;
}

# pattern 15
ABCDE
ABCD
ABC
AB
A
for(int i=0;i<n;i++){
  char x='A';
  for(int j=0;j<n-i;j++){
    cout<<x;
    x++;
    }
  cout<<endl;
}

# pattern 16
A
BB
CCC
DDDD
EEEEE
char x='A';
for(int i=0;i<n;i++){
  for(int j=0;j<=i;j++){
    cout<<x;
    }
     x++;
  cout<<endl;
}

# pattern 17
   A
  ABA
 ABCBA
ABCDCBA
for(int i=0;i<n;i++){
  for(int j=1;j<n-i;j++){
    cout<<" ";
    }
    char x='A';
    int b=(2*i + 1)/2;
  for(int j=0;j<((2*i)+1);j++){
      if(j<b){
          cout<<x;
          x++;
      }
      else{
          cout<<x;
          x--;
      }
    }
  cout<<endl;
}

# pattern 18
E
E D
E D C
E D C B
E D C B A
for(int i=0;i<n;i++){
    char c='E';
  for(int j=0;j<=i;j++){
    cout<<c<<" ";
    c--;
    }
  cout<<endl;
}

# pattern 19
**********
****  ****
***    ***
**      **
*        *
*        *
**      **
***    ***
****  ****
**********

# pattern 20
*        *
**      **
***    ***
****  ****
**********
****  ****
***    ***
**      **
*        *
  
# pattern 21
****
*  *
*  *
****

# pattern 22
4 4 4 4 4 4 4
4 3 3 3 3 3 4
4 3 2 2 2 3 4
4 3 2 1 2 3 4
4 3 2 2 2 3 4
4 3 3 3 3 3 4
4 4 4 4 4 4 4
