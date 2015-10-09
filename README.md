[![Build status](https://ci.appveyor.com/api/projects/status/nkdw5ed1m10fyrl2?svg=true)](https://ci.appveyor.com/project/gimoteco/escritaporextenso)
[![Total downloads](https://img.shields.io/nuget/dt/EscritaPorExtenso.svg)](https://www.nuget.org/packages/EscritaPorExtenso/)
[![Versão](https://img.shields.io/nuget/v/EscritaPorExtenso.svg)](https://www.nuget.org/packages/EscritaPorExtenso/)

# Escreva seus valores por extenso

# Instalando
``` powershell
Install-Package EscritaPorExtenso 
```
# Usando

## Para valores monetários em R$

``` csharp
using EscritaPorExtenso.Moeda;

//... 

1.99.PorExtensoDeReal(); // "um real e noventa e nove centavos"
```

## Para valores inteiros
``` csharp
using EscritaPorExtenso;

//...

1000.PorExtenso(); // "um mil"
```

Simples assim!
