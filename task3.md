# This task is to use RISC V GNU toolchain

#### Lab1 : c program to compute sum of n numbers.

```
#include<stdio.h>

int main() {
          int i,sum=0,n=5;
          for(i=1;i<=n;++i) {
          sum= +=i;
          }
  printf("Sum of numbers from 1 to %d is %d\n",n,sum);
  return 0;

}
```

1. open a file named sum1ton.c from the terminal as shown in the fig. 1 and type the above code into that file.

![Screenshot from 2024-02-24 20-00-00](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/e276927d-b079-4679-8fd3-fea5d84292ce)
<p align="centre">fig. 1</p>
<br>2. Save and close the file. If you do <b>ls</b> in the terminal then you should see the file as shown in the fig. 2

![Screenshot from 2024-02-24 19-57-41](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/503308a8-7771-4d8e-99b8-4fc66f5cbd47)
<p align="centre">fig. 2</p>
<br>3. To compile <b>c file</b> type the command as shown in fig. 3


![Screenshot from 2024-02-24 20-09-44](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/bc245b64-9539-4484-9497-0256e5de04d1)
<p align="centre">fig. 3</p>

<br>4. Upon successful compilation of the <b>c code</b> a file with a name <b>a.out</b> will be generated as shown in fig. 4

![Screenshot from 2024-02-24 20-16-46](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/4ef56b5a-b537-4886-875f-f29238b85523)
<p align="centre">fig. 4</p>

<br>5. To run the compiled code type the following as shown in the terminal which is shown in fig. 5
![Screenshot from 2024-02-24 20-20-49](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/dc5d2d36-6003-416f-852e-8ca092e29124)
<p align="centre">fig. 5</p>
<br>6. After running the compiled code result can be seen as shown in fig. 6

![Screenshot from 2024-02-24 20-23-41](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/9e036512-509f-4647-9361-8481a8fbf752)
<p align="centre">fig. 6</p>

