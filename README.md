# contoh-array-before-after-

    #include<stdio.h>

    void tukar(int array [2])
    {
    int t=array[0];
    array[0]=array[1];
    array[1]=t;
    }
    int main()
    {
    int array [2] = {1,2};
    printf("before %d = %d\n",array[0],array[1]);
    tukar(array);
    printf("after %d - %d",array[0],array[1]);
    }
    
![img](https://raw.githubusercontent.com/VIKTORKEVIN/contoh-array-before-after-/master/contoh%20array%20(before%20after).png)
