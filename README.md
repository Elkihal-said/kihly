<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>complex table</title>
    <style>
        .col22{
           position: relative;
           bottom: 250px;
        }
        .table{
            border-style : none;
        }
        .tableform{
            width: 625px;
            height : 432px;
            border : 1px solid black;
        }
        .col4{
            height : 23px;
        }
       
    </style>
</head>
<body>
    <div class="tableform">
        <table border="1" width="750" height="400" class="table">
            <tr1>
                <td rowspan="3">col1</td>
                <td rowspan="2">col2</td>
                <td colspan="2">col3</td>
                <td rowspan="3">col4</td>
                <td colspan="2">col5</td>
                
            </tr>
            <tr2>
                <td>col1</td>
                <td>col2</td>
                <td>col3</td>
                <td>col4</td>
              
            </tr>
            <tr3>
                <td colspan="2">col1</td>
                <td>col2</td>
                <td>col3</td>
                <td rowspan="3">col4</td>
                
                
            </tr>
            <tr4>
                <td>col1</td>
                <td colspan="2">col2</td>
                <td colspan="3">col3</td>
                
                
               
            </tr>
            <tr5>
                <td>col1</td>
                <td colspan="2">col2</td>
                
                <td rowspan="2">col4</td>
                <td colspan="2">col5</td>
                
                
            </tr>
            <tr6>
                <td>col1</td>
                <td colspan="2">col2</td>
                
                
                <td colspan="3">col5</td>
                
                
            </tr>
            <tr7>
                <td rowspan="5">col1</td>
                <td colspan="2" rowspan="3">col2</td>
                
                <td>col4</td>
                <td colspan="3">col5</td>
              
               
            </tr>
            <tr8>
                
                
                <td rowspan="4">col3</td>
                <td colspan="3" rowspan="4">col4</td>
                
                
            </tr>
            <tr9>
                
               
                
                
               
                
                
            </tr>
            <tr10>
                
                <td class="col22">colfd2</td>
                
               
               
                
            </tr>
            <tr11>
                
                <td>col2</td>
                
                
                <td>col7</td>
                
            </tr>
            <tr12>
                <td>col1</td>
                <td>col2</td>
              
    
                
            </tr>
            <tr13>
                <td>col1</td>
                <td colspan="4">col2</td>
               
                <td>col6</td>
                <td rowspan="2">col7</td>
                
            </tr>
            <tr14>
                <td colspan="3">col1</td>
                
                <td height=>col4</td>
                <td rowspan="3">col5</td>
                <td rowspan="3">col6</td>
                
                
            </tr>
            <tr15>
                <td colspan="3" rowspan="4">col1</td>
                
                
                
            </tr>
            <tr16>
                
                <td class="col4">col4</td>
                
                
                <td>col7</td>
                
            </tr>
            <tr17>
                
                <td>col4</td>
                <td>col5</td>
                <td>col6</td>
                <td>col7</td>
                
            </tr>
            <tr18>
                
                <td>col4</td>
                <td>col5</td>
                <td colspan="2" rowspan="2">col6</td>
                
                
            </tr>
            <tr19>
                <td>col1</td>
                <td colspan="2">col2</td>
              
                <td rowspan="3">col5</td>
                <td rowspan="3">col6</td>
                
                
                
            </tr>
            <tr20>
                <td>col1</td>
                <td>col2</td>
                <td>col3</td>
                
                <td colspan="2">col5</td>
               
               
               
            </tr>
            <tr>
                <td>col1</td>
                <td>col2</td>
                <td>col3</td>
                
                <td colspan="2">col5</td>
            
                
            </tr>
            
        </table>
    </div>
    
</body>
</html>
