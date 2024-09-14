# js-operators
<!DOCTYPE html>
<html lang="en">
    <head>
     <meta charset="UTF-8">
     <title>JS</title>
    </head>
    <body>
        <h3>demo on JS operators</h3>
        <script>
            let a=85, b=99, c="55";
            let s=a+b;
            //arithmatic
            document.write(s,"<br>");
            document.write(a*10,"<br>");
            document.write(2*15,"<br>");

            //relational
            document.write(a>=0,"<br>");
            document.write(b<a,"<br>");
            document.write(b==c,"<br>");
            document.write(b!=c,"<br>");
            document.write(b!==c,"<br>");

            //logical
            document.write(a>=1 && a<=100,"<br>");
            document.write(b==23 || b==33,"<br>");

            //assignment
            a+=30;  //a=a+30
            b%=10; //b=b%10;
            document.write(a,"<br>");
            document.write(b,"<br>");
            document.write(b++,"<br>"); //post incre 3 4
            document.write(++b,"<br>"); //pre incre 5 5
            document.write(a%2===0 ? "Even number": "Odd Number","<br>");
            document.write("rama"+"rao"+"<br>");
            document.write(true+b);
        </script>
    </body>
</html>
