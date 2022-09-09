# Pattern

## Aim:

## Equipment Required:

## Algorithm:

## Program:
```cs
using System;
public class Triangle
{
    public static void Main()
    {
        int row, val = 1, b, i, j;
        Console.Write("Number of Rows: ");
        row = Convert.ToInt32(Console.ReadLine());
        for (i = 0; i < row; i++)
        {
            for (b = 1; b <= row - i; b++)
                Console.Write("  ");
            for (j = 0; j <= i; j++)
            {
                if (j == 0 || i == 0)
                    val = 1;
                else
                    val = val * (i - j + 1) / j;
                Console.Write("{0}   ", val);
            }
            Console.Write("\n");
        }
    }
}
```

## Output:

![image](https://user-images.githubusercontent.com/74660507/189270423-6f545c5d-21cf-4591-85cd-d744ccb373b7.png)

## Result:
