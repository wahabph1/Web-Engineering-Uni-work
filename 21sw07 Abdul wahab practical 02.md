> # _**Practical: 02**_

#### **Task1: Create a time table of your class via combining different style,effects,color,size and padding**   
#### Solution:
Code:
```HTML
 <h1 style="text-align: center;">Task1</h1>
 <table border="1px">
        <caption>Time Table of 21SW 4th Semester</caption>
        <thead>
            <tr>
                <td>
                    Day/Time
                </td>
                <td>
                    8:30-9:30
                </td>
                <td>
                    9:30-10:30
                </td>
                <td>
                    10:30-11:00
                </td>
                <td>
                    11:00-12:00
                </td>
                <td>
                    12:00-1:00
                </td>
                <td>
                    1:00-2:00
                </td>
                <td>
                    2:00-3:00
                </td>
            </tr>
        </thead>
        <tbody style="text-align: center;">
            <tr>
                <td>MON</td>
                <td>SDA</td>
                <td>SDA</td>
                <td class="break-cell" rowspan="4">Break</td>
                <td colspan="3">We(PR)</td>
                <td>...</td>
            </tr>
            <tr>
                <td>Tue</td>
                <td colspan="2">CN(PR)</td>
                <td>CN(PR)</td>
                <td>Ent</td>
                <td>OR</td>
                <td>OR</td>
            </tr>
            <tr>
                <td>WED</td>
                <td colspan="2">SDA(PR)</td>
                <td>SDA(PR)</td>
                <td>CN</td>
                <td>CN</td>
                <td>SDA</td>
            </tr>
            <tr>
                <td>THU</td>
                <td>CN</td>
                <td>CN</td>
                <td>WE</td>
                <td>WE</td>
                <td>ENT</td>
                <td>ENT</td>
            </tr>
            <tr>
                <td>FRI</td>
                <td>OR</td>
                <td>OR</td>
                <td>WE</td>
                <td>WE</td>
                <td colspan="3">...</td>
            </tr>
        </tbody>
    </table>
```


> #### **Task Output**![task4.png](task4.png)

_**Task2: Create a table in HTML web page with zebra strip color style. With any border style.**_
#### Solution:

code:

```HTML 
 <h1 style="text-align: center;">Task2</h1>
<table   class="table2" border="1px">
    <thead>
        <tr>
            <th>Name</th>
            <th>Caste</th>
            <th>Roll Number</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Amor Ali Jatoi</td>
            <td>Jatoi</td>
            <td>21SW01</td>
        </tr>
        <tr>
            <td>Naxakat Umrani</td>
            <td>Umrani</td>
            <td>21SW49</td>
        </tr>
        <tr>
            <td>Abdul Wahab</td>
            <td>Shaikh</td>
            <td>21SW07</td>
        </tr>
    </tbody>
</table>
  <!-- CSS Part For Styling -->
<style>
    tr:nth-child(odd) {
        background-color: Black; 
    }
    tr:nth-child(even) {
        background-color: white; 
    }
    .table2{
        background-color: beige;
        border:  2px solid grey;
        border-bottom: 4px;
        border-top: 4px;
      box-shadow: 10px 10px 20px 6px khaki;  
    }
</style>
```
> #### **Task Output:** ![task5.png](task5.png)

_**Task3: Combine the styling from the two vertical and horizontal zebra strips effects every other row and every other column.
Note: If you use a transparent color you will get an overlapping effect.**_

Solution:

code:

```HTML CSS
<!-- HtML CODE -->
<table class="table3" border="1px">
    <caption></caption>
    
    <thead>
        <tr>
            <th>Name</th>
            <th>Caste</th>
            <th>Roll Number</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Amor Ali Jatoi</td>
            <td>Jatoi</td>
            <td>21SW01</td>
        </tr>
        <tr>
            <td>Naxakat Umrani</td>
            <td>Umrani</td>
            <td>21SW49</td>
        </tr>
        <tr>
            <td>Abdul Wahab</td>
            <td>Shaikh</td>
            <td>21SW07</td>
        </tr>
    </tbody>
</table>

<!-- CSS part for styling -->
 <style>
    .table3{
        background-color: aquamarine;
    }
    tr:nth-child(even) td:nth-child(odd),
    tr:nth-child(odd) td:nth-child(even){
        background-color: bisque;
    }
 </style> 
```
> #### **Task OutPut**: ![task6.png](task6.png)