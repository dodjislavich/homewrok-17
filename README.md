# homewrok-17
program fiftyfive;
var a,b,c,i :integer;
begin
for i := 2048 to 8192 do
begin
a := i mod 10;
if (i mod 7 = 0) and not(i mod 11 = 0) and not(i mod 23 = 0) then
if a <> 8 then writeln(i)
end;
for i := 12048 to 18192 do
begin
a := i mod 10;
if (i mod 7 = 0) and not(i mod 11 = 0) and not(i mod 23 = 0) then
if a <> 8 then writeln(i)
end;
end.

program fortyeight;
var a,b,c,i,max,min :integer;
begin
min:= 11200;
max:=0;
for i := 1221 to 11200 do
begin
a := i mod 10;
if (i mod 5 = 0) and not(i mod 7 = 0) and not(i mod 13 = 0) and not(i mod 17 = 0) and not(i mod 19 = 0) then inc(b);

if (i mod 5 = 0) and not(i mod 7 = 0) and not(i mod 13 = 0) and not(i mod 17 = 0) and not(i mod 19 = 0) then
if max < i then max:= i;

if (i mod 5 = 0) and not(i mod 7 = 0) and not(i mod 13 = 0) and not(i mod 17 = 0) and not(i mod 19 = 0) then
if min > i then min:= i;
end;
writeln(b);
writeln('max ', max);
writeln('min ', min);
end.


program fortynine;
var a,b,c,i :integer;
begin
for i := 1206 to 14992 do
begin
a := i mod 10;
if not(i mod 3 = 0) and not(i mod 4 = 0) and not(i mod 5 = 0) then
if (a = 3) or (a = 6) then writeln(i)
end;
end.


program fortyseven;
var a,b,c,i,max :integer;
begin
max:=0;
for i := 25552 to 58885 do
begin
b:=0;
for c:= 10 to 99 do
begin
if i mod c = 0 then inc (b);
if b>= 15 then inc(a);
if b>= 15 then
if max<i then max:=i;
end;
end;
writeln(a);
writeln (max);
end.
