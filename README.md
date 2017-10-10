
Program task2;
 var
  a,b,c,d,max: real;
 begin 
  writeln('Пожалуйста, введите числа a,b,c,d:');
  readln(a,b,c,d);
    if (a>b) and (a>c) and (a>d) then max:=a;
    if (b>c) and (b>d) then max:=b;
    if (c>d) then max:=c
     else
    max:=d;

    if (a<=b) and (b<=c) and (c<=d) then 
     begin
      a:=max;
      b:=max;
      c:=max;
      d:=max;
     end
     
      else
     
    if (a>b) and (b>c) then 
     begin
      a:=a;
      b:=b;
      c:=c;
      d:=d;
     end
     
      else
      
     begin
      a:=sqr(a);
      b:=sqr(b);
      c:=sqr(c);
      d:=sqr(d);
     end;
    write('Значения чисел после проверки:',' ',a,' ',b,' ',c,' ',d,' ');
    end.
 
