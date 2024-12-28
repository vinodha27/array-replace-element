# array-replace-element
int[] a={1,2,3,4,5,6,8,9,10};
        int num=7;
        int pos=7;
        for(int i=0;i<=a.length-1;i++)
        { 
            if(i==pos)
            {
                a[i]=num;
            }
              System.out.println(a[i]);
        }
