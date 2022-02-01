EJERCICIO 11
================
Dayeli Ruiz
31/1/2022

# EJERCICIO 11: crear función

``` r
Tc<- function(L,J){
  t<-0.3*(L/J^(1/4))^0.76
  print(t)
}
```

## Datos:

## L= 1200

## Cota sup. =190, cota inf.=80

``` r
Tc(L=1200,J=135)
```

    ## [1] 25.85447
