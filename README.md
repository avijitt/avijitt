<!DOCTYPE html>
<html>
<body>
  <script type="text/javascript">
    function multiply(){
      a=Number(document.my_cal.first.value);
      b=Number(document.my_cal.second.value);
      c=a*b;
      document.my_cal.total.value=c;
    }

    function addition(){
      a=Number(document.my_cal.first.value);
      b=Number(document.my_cal.second.value);
      c=a+b;
      document.my_cal.total.value=c;
    }


    function subtraction(){
      a=Number(document.my_cal.first.value);
      b=Number(document.my_cal.second.value);
      c=a-b;
      document.my_cal.total.value=c;
    }


    function division(){
      a=Number(document.my_cal.first.value);
      b=Number(document.my_cal.second.value);
      c=a/b;
      document.my_cal.total.value=c;
    }

    function modulus(){
      a=Number(document.my_cal.first.value);
      b=Number(document.my_cal.second.value);
      c=a%b;
      document.my_cal.total.value=c;
    }
  </script>

  <!-- Opening a HTML Form. -->
  <form name="my_cal">

    <!-- Here user will enter 1st number. -->
    Number 1: <input type="text" name="first">
    
    <br>

    <!-- Here user will enter 2nd number. -->
    Number 2: <input type="text" name="second">

    <br><br>

    <input type="button" value="ADD" onclick="javascript:addition();">
    <input type="button" value="SUB" onclick="javascript:subtraction();">
    <input type="button" value="MUL" onclick="javascript:multiply();">
    <input type="button" value="DIV" onclick="javascript:division();">
    <input type="button" value="MOD" onclick="javascript:modulus();">
   
    <br><br>

    <!-- Here result will be displayed. -->
    Get Result: <input type="text" name="total">

  </body>
  </html>

