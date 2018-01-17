# RWD-Flexbox-menu
This simply project shows how to use Flexbox.


http://the-echoplex.net/flexyboxes/
```

.flex-container {
    display: -webkit-flex;
    display: flex;
}

```


```

// liniowo (przy nowrap rozciąga kontener)

.inline-flex-container {
    display: -webkit-inline-flex;
    display: inline-flex;
}

```


### Flex-direction 

ustala kierunek i zwrot głównej osi:

- row - (domyślny) z lewej na prawą,
- column - z góry na dół,
- row-reverse - z prawej na lewą,
- column-revers - z dołu do góry.

```

-webkit-flex-direction: row;
 flex-direction: row;

```    
    
### Flex-wrap
- nowrap - (domyślny) wszystko w jednej linii,
- wrap -  zawija na końcu linii z góry na dół,
- wrap-reverse - zawija z dołu ku górze.
```

-webkit-flex-wrap: wrap;
    flex-wrap: wrap;

```    
    
### Justify-content
ustala rozmieszczenie elementów wzdłuż głównej osi (main-axis):
- flex-start - (domyślny) elementy będą umieszczone na początku linii,
- flex-end - na końcu linii,
- center - na środku,
- space-between - elementy będą rozciągnięte wzdłuż głównej osi; pierwszy będzie na początku linii, ostatni na końcu, a pozostałe będą rozmieszczone na środku,
- space-around - zachowane będą równe odległości pomiędzy poszczególnymi elementami; pierwszy i ostatni element będą oddalone od krawędzi kontenera jedynie o połowę odległości pomiędzy poszczególnymi komórkami.
```

-webkit-justify-content: flex-start;
    justify-content: flex-start;

```

### Align-items 
**działa przy jednej linii**
ustala rozmieszczenie elementów na osi poprzecznej (cross-axis) :
- flex-start - górne krawędzie elementów będą umieszczone przy górnej krawędzi kontenera,
- flex-end - analogicznie jak w przypadku flex-start, jednak dla dolnych krawędzi: będą one dociągnięte do dolnych krawędzi kontenera,
- center - elementy będą umieszczone centralnie na osi poprzecznej,
- baseline - elementy będą rozmieszczone tak, by zachować ich linię bazową, tj. by litery w poszczególnych elementach były umieszczone na jednej linii,
- stretch - zawartość będzie rozciągnięta, aby wypełnić kontener (warto przy tym zaznaczyć, że wartości min-width/max-width będą zachowane).

### Align-content 
**działa przy wiecej niż jednej linii**   
opcja jak w Justify-content


### Order
kolejność elementów na stronie
```
-webkit-order: -1;
    order: -1;
```     

**Flex-grow** - proporcjonalnie powiększa konkretny element    
**Flex-shrink** - pomniejsza   
**Flex-basis** - określa domyślny rozmiar elementu
```
-webkit-flex: 0 1 auto;
    flex: 0 2 auto;
```

**Align-self** - nadpisanie położenia
opcja jak w Align-items
