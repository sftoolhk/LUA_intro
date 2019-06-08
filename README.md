# LUA_intro
introdução a LUA

Operadores Relacionais

igual a     ==
maior que   >
menor que   <
maior ou igual a >=
menor ou igual a <=
diferente de ~=

Operadores logicos

Conjução (.E.)    and
Disjunção (.OU.)  or
negação (.NÃO.)   not

if (condição) then
  ação
end

if (condição) then
  ação
else
  ação
end

while (condição) do
  ação
end

repeat
  ação
until (condição)


for var = inicial, fim, incremento do
  ação
end

a = tonumber (io.read())
b = tonumber (io.read())
if (a > b) then
  r = a - b
else
  r = b - a
end
print ("r = ", r)


