# footballmatch
 База данных футбольных матчей. Таблица команд (название, город, страна). Таблица матчей (дата, команда, команда, счет, место проведения). Таблица футболистов (команда, ФИО, зарплата в год, возраст).



Program  footballmatch; 
uses Crt;
var
  b, i, i2: byte;
  m: array [1..9] of string;
  
procedure proc1;
var
c: char; 
begin
Writeln('Введите строку');
Readln(c);
end;
{proc1 = }
procedure proc2;
begin
end;
{proc2 = }
procedure proc3;
begin
end;
{proc3 = }
procedure proc4;
begin
end;
{proc4 = }
procedure proc5;
begin
end;
{proc5 = }
procedure proc6;
begin
end;
//proc6 = 
procedure proc7;
begin
end;
// proc 7 =
procedure proc8;
begin
end;
// proc 8 =
 

begin
  TextBackground(white); //Задаем цвет фона
  textcolor(LightMagenta);//Задаем цвет текста 
    m[1] := '*Добавление строки - 1*';
    m[2] := '*Вывод на экран - 2*';
    m[3] := '*Удаление - 3*';
    m[4] := '**';
    m[5] := '**';
    m[6] := '**';
    m[7] := '**';
    m[8] := '**';
    m[9] := '*Для Выхода введите - 0*';
    
repeat
ClrScr;
for i:= 1 to 9 do 
  begin// Выыод меню на экран
    for i2:= 1 to length(m[i]) do//
      write('*');//
      writeln();//
      writeln(m[i]);//
    for i2:= 1 to length(m[i]) do//
      write('*');//
      writeln();//
  end;
Readln(b);
  case b of
    1: proc1;
    2: proc2;
    3: proc3;
    5: proc5;
    6: proc6;
    7: proc7;
    8: proc8;
  end;
until b = 0;
end.
   
  



